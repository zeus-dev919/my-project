<template>
  <div className='container px-32 pt-10 '>
      <div className='grid grid-cols-12 gap-8'>
        <div className='col-span-7'>
          <div className='w-full h-auto mb-8'>
            <div className='py-4 pl-6 text-2xl font-extrabold'>About</div>
            <div className='grid w-full h-auto grid-rows-3 gap-4 px-6 py-8 border-2 border-gray-200 rounded-2xl'>
              <div className='h-auto'>
                <div className='inline mr-2 font-bold '>Topics:</div>
                <div className='inline-block px-6 py-2 mx-2 text-gray-400 border-2 border-gray-200 rounded-2xl bg-slate-100'>productivity</div>
                <div className='inline-block px-6 py-2 mx-2 text-gray-400 border-2 border-gray-200 rounded-2xl bg-slate-100'>new tools</div>
                <div className='inline-block px-4 py-2 mx-2 text-gray-400 border-2 border-gray-200 rounded-full bg-slate-100'>+</div>
              </div>
              <div>
                <div className='inline mr-2 font-bold '>Attendees:</div>
                <img className="inline-block mx-2 rounded-full h-9 w-9 ring-2 ring-white" />
                <img className="inline-block mx-2 rounded-full h-9 w-9 ring-2 ring-white" />
                <img className="inline-block mx-2 rounded-full h-9 w-9 ring-2 ring-white" />
                <div className='inline-block px-4 py-2 mx-2 text-gray-400 border-2 border-gray-200 rounded-full bg-slate-100'>+</div>
              </div>
              <div>
                <div className='inline mr-2 font-bold '>Notes:</div>
                <div className='inline-block px-4 py-2 mx-2 text-gray-400 border-2 border-gray-200 rounded-full bg-slate-100'>+</div>
              </div>
            </div>
          </div>
          <div className='w-full h-auto'>
            <div className='flex justify-between pl-6 mb-2'>
              <div className='py-3 text-2xl font-extrabold'>Summary</div>
              <button className='px-10 font-bold text-white bg-[#fe993e] rounded-full'>Edit</button>
            </div>
            <div className='flex flex-col h-screen space-y-1 border-2 border-gray-200 rounded-2xl scroll-mr-16'>
              <div className='grid grid-cols-12 gap-4 py-4 pl-6 pr-2 mr-2 border-2 border-yellow-500 rounded-2xl bg-[#fef2ee]'>
                <div className='flex items-center justify-center w-10 h-10 col-span-1 border-2 border-yellow-500 text-[#fe993e] rounded-full text-md'>1</div>
                <div className='inline-block col-span-11 '> img elements must have an alt prop, either with meaningful text, or an empty string for decorative images</div>
              </div>
              <div className='grid grid-cols-12 gap-4 py-4 pl-6 pr-2 mr-2 border-2 border-[#ac90e3]  rounded-2xl bg-[#ebe3f9]'>
                <div className='flex items-center justify-center w-10 h-10 col-span-1 border-2 text-[#ac90e3]  border-[#ac90e3] rounded-full text-md'>2</div>
                <div className='inline-block col-span-11 '> img elements must have an alt prop, either with meaningful text, or an empty string for decorative images</div>
              </div>
            </div>

          </div>
        </div>
        <div className='h-auto col-span-5 '>
          <div className='flex justify-between pl-6 mb-2'>
            <div className='py-3 text-2xl font-extrabold'>Transcript</div>
          </div>
          <div className='flex flex-col space-y-1 h-[1080px] border-2 border-gray-200 rounded-2xl scroll-mr-16'>
            {/* orange */}
            <div className='py-4 pl-6 pr-2 mr-2 border-2 border-yellow-500 rounded-2xl bg-[#fef2ee]'>
              <div className='grid grid-cols-12 gap-4'>
                <img className="inline-block col-span-2 mx-2 rounded-full h-9 w-9 ring-2 ring-white" />
                <div className='inline-block col-span-10 '>
                  <div className='block pb-6 font-bold'>Patricia | 00:00:05</div>
                  <div className='text-gray-500 '>img elements must have an alt prop, either with meaningful text, or an empty string for decorative images</div>
                </div>
              </div>
            </div>

            {/* purple */}
            <div className='py-4 pl-6 pr-2 mr-2 border-2 border-[#ac90e3] rounded-2xl bg-[#ebe3f9]'>
              <div className='grid grid-cols-12 gap-4'>
                <img className="inline-block col-span-2 mx-2 rounded-full h-9 w-9 ring-2 ring-white" />
                <div className='inline-block col-span-10 '>
                  <div className='block pb-6 font-bold'>Jack | 00:00:54</div>
                  <div className='text-gray-500 '>img elements must have an alt prop, either with meaningful text, or an empty string for decorative images</div>
                </div>
              </div>

              <div className='grid grid-cols-12 gap-4 py-6 align-middle'>
                <div className='inline-block col-span-2' />
                <div className='inline-block col-span-8 border-t-2 border-white' />
                <div className='flex items-center justify-center w-10 h-10 col-span-2 -mt-5 text-white border-2 border-white rounded-full'>+</div>
              </div>

              <div className='grid grid-cols-12 gap-4'>
                <img className="inline-block col-span-2 mx-2 rounded-full h-9 w-9 ring-2 ring-white" />
                <div className='inline-block col-span-10 '>
                  <div className='block pb-6 font-bold'>Jack | 00:00:54</div>
                  <div className='text-gray-500 '>img elements must have an alt prop, either with meaningful text, or an empty string for decorative images</div>
                </div>
              </div>
            </div>

            <div className='py-4 pl-6 pr-2 mr-2 border-2 border-yellow-500 rounded-2xl bg-[#fef2ee]'>
              <div className='grid grid-cols-12 gap-4'>
                <img className="inline-block col-span-2 mx-2 rounded-full h-9 w-9 ring-2 ring-white" />
                <div className='inline-block col-span-10 '>
                  <div className='block pb-6 font-bold'>Patricia | 00:02:13</div>
                  <div className='text-gray-500 '>img elements must have an alt prop, either with meaningful text, or an empty string for decorative images</div>
                </div>
              </div>

              <div className='grid grid-cols-12 gap-4 py-6 align-middle'>
                <div className='inline-block col-span-2' />
                <div className='inline-block col-span-8 border-t-2 border-white' />
                <div className='flex items-center justify-center w-10 h-10 col-span-2 -mt-5 text-white border-2 border-white rounded-full'>+</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<style>
.nuxt-logo {
  height: 180px;
}
</style>
