<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k9_n8ibqn"/><path class="zx5lk7bcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:keyframes-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k9_n8ibqn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m14 10l2 2l-4 4l-4-4l4-4Z");
}

.zx5lk7bcf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 10l2 2l-4 4l-4-4l4-4zM5 9l-3 3l3 3m14-6l3 3l-3 3");
}

</style>
