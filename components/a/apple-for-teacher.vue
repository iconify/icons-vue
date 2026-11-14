<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rjtdfimjy"/><path class="dlii5sbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apple-for-teacher" /></template>
<style>
.dlii5sbbk {
  d: path("M12 7.5c0-2 .75-3.5 2.5-4.5m-1 2.25C14.25 3.5 16 2.75 18.25 3c-.25 1.75-2 2.75-4.75 2.25Z");
}

.rjtdfimjy {
  d: path("M12 7.5c-1.5-1-3.25-1.25-4.75-.75C4.5 7.75 3.75 11 4.5 14c.75 3.5 3.25 6.5 5.5 6.5c.75 0 1.25-.5 2-.5s1.25.5 2 .5c2.25 0 4.75-3 5.5-6.5c.75-3 0-6.25-2.75-7.25c-1.5-.5-3.25-.25-4.75.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
