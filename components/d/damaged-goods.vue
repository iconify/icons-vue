<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bk3f2dbig"/><path class="a3w98y88g"/><path class="wdlekd8nk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:damaged-goods" /></template>
<style>
.a3w98y88g {
  d: path("M2.5 8h13v13.5h-13Z");
}

.bk3f2dbig {
  d: path("m5.248 6.168l3-2A1 1 0 0 1 8.803 4h9.394a1 1 0 0 1 .555 1.832l-3 2a1 1 0 0 1-.555.168H5.803a1 1 0 0 1-.555-1.832Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wdlekd8nk {
  d: path("m15.945 7.703l4-2.667a1 1 0 0 1 1.555.833v11.096a1 1 0 0 1-.445.832l-4 2.667a1 1 0 0 1-1.555-.833V8.535a1 1 0 0 1 .445-.832ZM9.5 8l-2 3.5l3 2.5L8 17.5l1 4M12 6h6");
}

</style>
