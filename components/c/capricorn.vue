<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGLsIEmbng" class="sxmreca9p"/></defs><circle class="z6nvowbsd"/><circle class="uuhw7zbpi"/><path class="xavh2tbsb"/><use href="#SVGLsIEmbng" class="e0ty9gbgt"/><path class="z_ruwl65v"/><use href="#SVGLsIEmbng" class="pfsdhbbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:capricorn" /></template>
<style>
.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

.sxmreca9p {
  fill: var(--svg-color--a08ccf, #a08ccf);
  d: path("M24 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5c-9.3 3-17.9 6.4-23.1 14.3c-2 3-4.9 14.4-8.6 12.3c-3.9-2.3-3.1-9.5 2.6-18.3");
}

.uuhw7zbpi {
  cx: 60.1px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--7e57c2, #7e57c2);
}

.xavh2tbsb {
  fill: var(--svg-color--5e35b1, #5e35b1);
  d: path("M94.8 84.1c-1.6.8-3.4 1.6-6.5 1.6c-2 0-4.6-.4-8.1-1.3c-.4-.1-.6-.4-.6-.8c-.1-8 1.8-12.1 3.6-14.2c1.8-2 3.4-3.1 6.5-3.1h.3c3 0 5.3 1.3 7.5 4c5.5 6.5-.4 12.7-2.7 13.8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z_ruwl65v {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M103.9 65.3c-3.5-5.1-7.8-7-13.5-7c-15.6.1-18.5 16.1-18.7 22.5c0 .3-.3.5-.6.4l-1.1-.5c-2-.7-2.8-4.8-3-7.4V44.6c0-8.7-6.8-16.1-15.5-16.4c-5-.2-9.5 2-12.5 5.4c-1.1-1.2-2.3-2.3-3.8-3.1c-2.1-1.3-4.9-.5-5.8 1.8c-.8 1.9 0 4 1.6 5c2.4 1.4 4 4 4 6.9V82c0 2.1 1.5 3.9 3.6 4.2c2.4.2 4.4-1.6 4.4-4V44.4c0-4.3 3.2-8 7.5-8.3c4.7-.3 8.5 3.4 8.5 8v30c.3 3.8 1.6 11.6 8.2 14.1q.3.15.9.3c.8.3 2 .8 3.3 1.3c.4.1.6.4.7.8s.1.8.2 1.2c.4 3.1-.6 4.2-2.3 4.9c-3.1 1.4-8 1.1-12.3.2c-2.5-.5-4.8 1.4-4.8 3.9c0 1.9 1.3 3.5 3.2 3.9c1.4.3 2.8.5 4.2.7c1.3.1 2.7.2 4.1.2c3.7 0 7.8-.6 10.9-2.8c3.2-2.2 5-5.7 5-9.9c0-.3.2-.5.5-.4c22.5 6.4 31.2-15.4 23.1-27.2m-9.1 18.8c-2.7 1.3-5.9 2.7-14.6.2c-.4-.1-.6-.4-.6-.8c-.1-8 1.8-12.1 3.6-14.2c1.8-2 3.4-3.1 6.5-3.1c3.1-.1 5.5 1.2 7.8 3.9c5.5 6.6-.4 12.9-2.7 14");
}

.z6nvowbsd {
  cx: 64px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--5e35b1, #5e35b1);
}

</style>
