<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="emip1cbcf"/><path class="qx-wxxe9w"/><path class="xldyl2z1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:angiogram" /></template>
<style>
.emip1cbcf {
  d: path("M3 4.5a2 2 0 0 1 2-2h12.5L21 6v13.5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.qx-wxxe9w {
  d: path("M12 19.5c0-3-.5-5-2-7m0 0c-1.5-2-2.5-4-2.5-7m2.5 7c2-1.75 3.5-3.25 4.5-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xldyl2z1d {
  d: path("M11.75 15.75c1.75-1 3.75-1.25 5.75-3.25m-9-2.5c-1.25-.25-2.25.25-3 1.25");
}

</style>
