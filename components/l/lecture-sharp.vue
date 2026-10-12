<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tlkzz9bje"/><circle class="wijmr5spd"/><path class="yt0k09bcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lecture-sharp" /></template>
<style>
.tlkzz9bje {
  d: path("M6.25 11.75h13l-.23 1.48l-1.04 6.54l-.23 1.48H6.25l-.23-1.48l-1.04-6.54l-.23-1.48z");
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yt0k09bcz {
  d: path("m16.75 11.75l1.5-3.5m-8 8h3.5");
}

</style>
