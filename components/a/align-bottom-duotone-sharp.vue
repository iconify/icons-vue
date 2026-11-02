<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hvi065bak"/><path class="luk7ikbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-bottom-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hvi065bak {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 16V4h6v12Zm10 0V8h6v8Z");
}

.luk7ikbdd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4v12h6V4Zm10 4v8h6V8ZM3 20h18");
}

</style>
