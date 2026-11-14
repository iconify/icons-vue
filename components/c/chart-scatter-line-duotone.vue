<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m3437h1_z"/><path class="d6n8bebxi"/><path class="c2d9wubwx"/><path class="sxukntb1f"/><path class="bu5evrbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-scatter-line-duotone" /></template>
<style>
.bu5evrbia {
  d: path("M21 6C21 6.8284 20.3284 7.5 19.5 7.5C18.6716 7.5 18 6.8284 18 6C18 5.1716 18.6716 4.5 19.5 4.5C20.3284 4.5 21 5.1716 21 6Z");
}

.c2d9wubwx {
  d: path("M12.5 9.5C12.5 10.3284 11.8284 11 11 11C10.1716 11 9.5 10.3284 9.5 9.5C9.5 8.6716 10.1716 8 11 8C11.8284 8 12.5 8.6716 12.5 9.5Z");
}

.d6n8bebxi {
  d: path("M9 15.5C9 16.3284 8.3284 17 7.5 17C6.6716 17 6 16.3284 6 15.5C6 14.6716 6.6716 14 7.5 14C8.3284 14 9 14.6716 9 15.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m3437h1_z {
  d: path("M22 22H6C4.1144 22 3.1716 22 2.5858 21.4142C2 20.8284 2 19.8856 2 18V2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sxukntb1f {
  d: path("M17 13.5C17 14.3284 16.3284 15 15.5 15C14.6716 15 14 14.3284 14 13.5C14 12.6716 14.6716 12 15.5 12C16.3284 12 17 12.6716 17 13.5Z");
}

</style>
