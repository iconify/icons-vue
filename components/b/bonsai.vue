<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sj7npt9ph"/><path class="m740b7bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bonsai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m740b7bws {
  d: path("M12 17c0-2.5-1.25-3.5-.75-5.5s1.75-1.6 3-1.9m-2.85 2.7l-2.15-.7m-4 5.4h13.5q.75 0 .46.69l-1.17 2.87q-.29.69-1.04.69H7q-.75 0-1.04-.69l-1.17-2.87Q4.5 17 5.25 17");
}

.sj7npt9ph {
  d: path("M6.75 4a3.25 1.25 0 1 0 6.5 0a3.25 1.25 0 1 0-6.5 0M3.5 10a4 2.25 0 1 0 8 0a4 2.25 0 1 0-8 0m8.75-2.5a4.25 2.5 0 1 0 8.5 0a4.25 2.5 0 1 0-8.5 0");
}

</style>
