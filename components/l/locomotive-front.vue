<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="frjnuhbxx"/><path class="i4ywq3bup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:locomotive-front" /></template>
<style>
.frjnuhbxx {
  d: path("M4.5 19.5v-11a5 5 0 0 1 5-5h5a5 5 0 0 1 5 5v11Z");
}

.i4ywq3bup {
  d: path("M7.5 6.5h9v4h-9Zm2.75 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM8 19.5l-2 2m10-2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
