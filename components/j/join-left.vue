<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xxxcdij5x"/><path class="u3v3lgbld"/><path class="pxb1wbcry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:join-left" /></template>
<style>
.pxb1wbcry {
  fill: currentColor;
  d: path("M4 9.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm0 5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm7-2.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.u3v3lgbld {
  d: path("M10 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxxcdij5x {
  d: path("M2 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

</style>
