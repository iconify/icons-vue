<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x25-53pzd"/><path class="i4s_igs0m"/><path class="zfizmub5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bleeding-control" /></template>
<style>
.i4s_igs0m {
  fill: currentColor;
  d: path("M19 13c1.25 1.5 2.25 2.75 2.25 4c0 1.4-1 2.5-2.25 2.5s-2.25-1.1-2.25-2.5c0-1.25 1-2.5 2.25-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x25-53pzd {
  d: path("M6.75 17.25v-2l-2.5-3.5c-.5-.75-.5-1.75.25-2c.5-.5 1.25-.25 1.75.5l1 1.25V4.75c0-.5.5-1 1-1c.75 0 1.25.5 1.25 1v4.5v-5.5c0-.75.5-1.25 1.25-1.25c.5 0 1 .5 1 1.25v5.5v-4.5c0-.5.75-1 1.25-1c.75 0 1.25.5 1.25 1V9.5V6.75c0-.5.5-1.25 1-1.25c.75 0 1.25.75 1.25 1.25v5.5c0 2.25-1.5 3.5-2.75 3.5v1.5");
}

.zfizmub5v {
  d: path("M4.5 20h12");
}

</style>
