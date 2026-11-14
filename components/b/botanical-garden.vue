<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h3_4q0bmq"/><path class="fy-i81bly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:botanical-garden" /></template>
<style>
.fy-i81bly {
  d: path("M12 15.5c-2.5 0-4-1.5-4-4c2.5 0 4 1.5 4 4Zm0-2c0-2.5 1.5-4 4-4c0 2.5-1.5 4-4 4Z");
}

.h3_4q0bmq {
  d: path("M3.5 21V11a8.5 8.5 0 0 1 17 0v10Zm8.5-.5v-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
