<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":205};
const content = `<defs><linearGradient x1="49.999%" y1=".296%" x2="49.999%" y2="99.98%" id="ssvg-id-doubleclicka"><stop offset="0%" class="frt4b8bjz"/><stop offset="60%" class="lidx78buw"/></linearGradient><linearGradient x1="49.999%" y1="99.433%" x2="49.999%" y2="-.09%" id="ssvg-id-doubleclickb"><stop offset="0%" class="frt4b8bjz"/><stop offset="60%" class="lidx78buw"/></linearGradient><linearGradient x1="32.539%" y1="17.488%" x2="77.945%" y2="128.204%" id="ssvg-id-doubleclickc"><stop offset="0%" class="xnf2tubjp"/><stop offset="75%" class="j8etffcta"/></linearGradient><linearGradient x1="5.239%" y1="50.028%" x2="136.165%" y2="50.028%" id="ssvg-id-doubleclickd"><stop offset="0%" class="pxovqgbsq"/><stop offset="60%" class="lidx78buw"/></linearGradient></defs><path class="rk0i0qbhs"/><path class="imq1wkhuu"/><path fill="url(#ssvg-id-doubleclicka)" class="rzarlacfu"/><path fill="url(#ssvg-id-doubleclickb)" class="vmf5-5bbg"/><path fill="url(#ssvg-id-doubleclickc)" class="a49qtobvf"/><path fill="url(#ssvg-id-doubleclickd)" class="n47-8xbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:doubleclick" /></template>
<style>
.a49qtobvf {
  d: path("M127.765 201.295C84.488 190.02 52.03 151.162 51.269 104.23v-.305v.762c.61 39.771 14.781 75.124 37.029 99.047c4.724.61 9.295 1.067 14.019 1.067c8.686-.305 17.524-1.371 25.448-3.505z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.frt4b8bjz {
  stop-color: var(--svg-color--fff, #FFF);
  stop-opacity: 0.6;
}

.imq1wkhuu {
  d: path("M127.848 3.352C119.619 1.22 111.086 0 102.4 0C45.867 0 0 45.867 0 102.4c0 56.533 45.867 102.248 102.248 102.248c8.838 0 17.219-1.067 25.447-3.353C84.42 190.02 51.962 151.162 51.2 104.23v-3.962c1.067-27.429 23.619-49.372 51.048-49.372c9.295 0 18.133 2.438 25.447 6.857c15.39 8.838 25.448 25.296 25.448 44.496c0 19.2-10.362 35.338-25.448 44.48c7.62 4.115 13.094 6.64 25.747 7.036c27.72.867 50.602-21.676 51.206-53.345c-.762-46.933-33.22-86.095-76.8-97.067z");
  fill: var(--svg-color--aeea00, #AEEA00);
}

.j8etffcta {
  stop-color: var(--svg-color--fff, #FFF);
  stop-opacity: 0.03;
}

.lidx78buw {
  stop-color: var(--svg-color--fff, #FFF);
  stop-opacity: 0.1;
}

.n47-8xbvh {
  d: path("M113.363 66.362c.761.305 2.167.868 2.93 1.02c3.352-3.505 7.526-7.103 11.64-9.54c-7.466-4.42-16.674-6.91-25.97-6.91c-27.733 0-50.162 22.287-50.924 49.716l-.153 1.676c-.304-.61-.152-1.22.153-1.676c7.924-26.362 35.352-41.753 62.324-34.286z");
  opacity: var(--svg-opacity--0-25, 0.25);
}

.pxovqgbsq {
  stop-color: var(--svg-color--fff, #FFF);
  stop-opacity: 0.9;
}

.rk0i0qbhs {
  d: path("M128 3.513c44.467 12.025 75.494 50.277 76.256 96.906v3.691c-1.395 27.065-22.78 49.343-50.209 49.343c-9.295 0-18.58-2.139-25.895-6.558c-15.39-8.838-25.6-25.295-25.6-44.495c0-19.2 10.362-35.352 25.448-44.495c-7.467-4.42-16.91-7.513-26.206-7.513c-27.733 0-50.16 22.598-51.074 50.027v4.67c.762 46.933 34.004 85.387 77.585 96.359c8.228 2.133 16.762 3.352 25.447 3.352C210.286 204.8 256 158.933 256 102.552C256 45.867 210.133 0 153.6 0c-8.838 0-17.371 1.227-25.6 3.513z");
  fill: var(--svg-color--369647, #369647);
}

.rzarlacfu {
  d: path("M204.648 100.419c-.762-46.933-33.22-86.095-76.8-97.067C119.619 1.22 111.086 0 102.4 0C45.867 0 0 45.867 0 102.4c0 56.533 45.867 102.248 102.248 102.248c8.838 0 17.219-1.067 25.447-3.353C84.42 190.02 51.962 151.162 51.2 104.23v-3.962c1.067-27.429 23.619-49.372 51.048-49.372c9.295 0 18.133 2.438 25.447 6.857c15.39 8.838 25.448 25.296 25.448 44.496c0 19.2-10.362 35.352-25.448 44.495c7.62 4.114 16.457 6.857 25.753 6.857c27.733 0 50.133-21.943 51.047-49.371v-1.981c.153-.458.153-1.22.153-1.829z");
  opacity: var(--svg-opacity--0-15, 0.15);
}

.vmf5-5bbg {
  d: path("M153.6 0c-8.838 0-17.219 1.067-25.448 3.352c43.581 11.277 76.038 50.438 76.8 97.067v3.962c-1.066 27.429-23.923 49.371-51.352 49.371c-9.295 0-18.133-2.438-25.448-6.857c-15.39-8.838-25.6-25.295-25.6-44.495c0-19.2 10.362-35.352 25.448-44.495c-7.467-4.42-16.152-6.857-25.448-6.857c-27.733 0-50.133 21.942-51.047 49.371v3.962c.762 46.933 33.219 86.095 76.8 97.067c8.228 2.133 16.762 3.352 25.447 3.352C210.286 204.8 256 158.933 256 102.552C256 45.867 210.133 0 153.6 0z");
  opacity: var(--svg-opacity--0-15, 0.15);
}

.xnf2tubjp {
  stop-color: var(--svg-color--fff, #FFF);
  stop-opacity: 0.5;
}

</style>
