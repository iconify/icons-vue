<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xdtd3ebiq"/><path class="xgaaqqcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:field-notebook" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdtd3ebiq {
  d: path("M12 6c-2.5-1.5-6-1.5-9.5-.5v13c3.5-1 7-1 9.5.5c2.5-1.5 6-1.5 9.5-.5v-13c-3.5-1-7-1-9.5.5Z");
}

.xgaaqqcec {
  d: path("m6.92 13.201l6.928-4l2.915.049l-1.415 2.549l-6.928 4Zm6.928-4l1.5 2.598");
}

</style>
