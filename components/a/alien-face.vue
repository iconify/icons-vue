<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iodw-z-yl"/><path class="dh9sb2b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alien-face" /></template>
<style>
.dh9sb2b2w {
  d: path("M7.5 10.5c1.5 0 3 1 3 2.5c-1.5 0-3-1-3-2.5m9 0c-1.5 0-3 1-3 2.5c1.5 0 3-1 3-2.5M11 17h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iodw-z-yl {
  d: path("M12 5c4.1 0 7.25 2.75 7.25 6.5c0 4.5-4.1 9.75-7.25 9.75S4.75 16 4.75 11.5C4.75 7.75 7.9 5 12 5m-2.75.4L7.5 3m7.25 2.4L16.5 3");
}

</style>
