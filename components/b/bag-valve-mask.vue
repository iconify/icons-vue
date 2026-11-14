<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="owa615r0n"/><path class="ggw5jfb2i"/><path class="wlv-50ymu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bag-valve-mask" /></template>
<style>
.ggw5jfb2i {
  fill: currentColor;
  d: path("M16.5 9.5c3.5-.5 5.25 2 5.25 4.5c0 2.75-2 4.5-5 4.75c-1-3-1-6.25-.25-9.25Z");
}

.owa615r0n {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7c0-3.288 1.945-5.977 4.793-7.026");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wlv-50ymu {
  d: path("M12 4.5a4.75 2.25 0 1 0 9.5 0a4.75 2.25 0 1 0-9.5 0Zm7 2.25v2.5");
}

</style>
