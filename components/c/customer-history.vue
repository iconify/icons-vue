<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nz28kcb1l"/><path class="ly0allbrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:customer-history" /></template>
<style>
.ly0allbrh {
  d: path("m13.25 16.5l1.5 1.5l1.5-1.5");
}

.nz28kcb1l {
  d: path("M12.634 21H3.5c-.6 0-1-.4-1-1c0-2.75 2.9-4.75 6.5-4.75q.728 0 1.41.106M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm9.5 9.5a3.25 3.25 0 1 1 1.5 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
