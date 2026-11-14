<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ixpzelbmk"/><path class="wb7rpab6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compliance-training" /></template>
<style>
.ixpzelbmk {
  d: path("M12 6.5C10 5 6.5 4.5 2.5 5v14c4-.5 7.5 0 9.5 1.5c2-1.5 5.5-2 9.5-1.5V5c-4-.5-7.5 0-9.5 1.5Zm0 0v14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wb7rpab6r {
  d: path("m14.75 12l1.5 1.5L19 10");
}

</style>
