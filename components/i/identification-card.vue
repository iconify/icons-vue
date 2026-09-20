<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jnyikxcds"/><path class="mhla_wtek"/><linearGradient id="SVGlOZnpcAG" x1="28.813" x2="28.813" y1="74.347" y2="38.979" gradientTransform="matrix(1 0 0 -1 0 128.11)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="r5vbxk1ae"/><stop offset="1" class="f267jt5sf"/></linearGradient><path fill="url(#SVGlOZnpcAG)" class="vy_u43bva"/><path class="sqiqamzkn"/><path class="fpi9ddc7i"/><path class="hepn6u97h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:identification-card" /></template>
<style>
.f267jt5sf {
  stop-color: var(--svg-color--1565c0, #1565c0);
}

.fpi9ddc7i {
  fill: var(--svg-color--82aec0, #82aec0);
  d: path("M79.09 53.76H54.33c-1.31 0-2.37-1.06-2.37-2.37s1.06-2.37 2.37-2.37h24.76c1.31 0 2.37 1.06 2.37 2.37a2.38 2.38 0 0 1-2.37 2.37m8.87 11.79H54.33c-1.31 0-2.37-1.06-2.37-2.37s1.06-2.37 2.37-2.37h33.63c1.31 0 2.37 1.06 2.37 2.37a2.38 2.38 0 0 1-2.37 2.37M75.27 77.34H54.33c-1.31 0-2.37-1.06-2.37-2.37s1.06-2.37 2.37-2.37h20.94c1.31 0 2.37 1.06 2.37 2.37a2.38 2.38 0 0 1-2.37 2.37m-5.7 11.79H54.33c-1.31 0-2.37-1.06-2.37-2.37s1.06-2.37 2.37-2.37h15.24c1.31 0 2.37 1.06 2.37 2.37s-1.06 2.37-2.37 2.37");
}

.hepn6u97h {
  fill: var(--svg-color--94d1e0, #94d1e0);
  d: path("M124 53.79c-.17-.01-.34-.03-.52-.03c-7.84 0-14.19 6.35-14.19 14.19s6.35 14.19 14.19 14.19c.17 0 .34-.02.52-.03z");
}

.jnyikxcds {
  fill: var(--svg-color--b9e4ea, #b9e4ea);
  d: path("M4 93.33V34.67c0-4.68 3.83-8.5 8.5-8.5h103c4.68 0 8.5 3.83 8.5 8.5v58.67c0 4.68-3.83 8.5-8.5 8.5h-103c-4.67 0-8.5-3.83-8.5-8.51");
}

.mhla_wtek {
  fill: var(--svg-color--fff, #fff);
  d: path("M42.43 89.13H15.19c-.85 0-1.54-.69-1.54-1.54V50.57c0-.85.69-1.54 1.54-1.54h27.24c.85 0 1.54.69 1.54 1.54V87.6c0 .84-.69 1.53-1.54 1.53");
}

.r5vbxk1ae {
  stop-color: var(--svg-color--1e88e5, #1e88e5);
}

.sqiqamzkn {
  fill: var(--svg-color--2f7889, #2f7889);
  d: path("M115.5 26.16h-103c-4.68 0-8.5 3.83-8.5 8.5v5.33h120v-5.33c0-4.67-3.83-8.5-8.5-8.5");
}

.vy_u43bva {
  d: path("M43.87 87.95v1.18H13.75v-1.18c0-4.63 5.87-6.87 12.38-7.34v-.32c-2.74-.83-5.19-2.89-6.4-6.28c-1.24-.44-1.95-4.51-1.62-5.04c-.24-1.71-1.86-15.12 10.7-15.21c12.53.06 10.93 13.44 10.67 15.18c.32.53-.38 4.6-1.62 5.04c-1.18 3.39-3.63 5.48-6.37 6.31v.29c6.55.53 12.38 3.01 12.38 7.37");
}

</style>
