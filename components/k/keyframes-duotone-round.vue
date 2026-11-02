<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ja6u_lsgr"/><path class="qkrtfp54v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:keyframes-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ja6u_lsgr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m14 10l1 1a1.415 1.415 0 0 1 0 2l-2 2a1.415 1.415 0 0 1-2 0l-2-2a1.415 1.415 0 0 1 0-2l2-2a1.415 1.415 0 0 1 2 0Z");
}

.qkrtfp54v {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 10l1 1a1.414 1.414 0 0 1 0 2l-2 2a1.414 1.414 0 0 1-2 0l-2-2a1.414 1.414 0 0 1 0-2l2-2a1.414 1.414 0 0 1 2 0zM5 9l-2 2a1.414 1.414 0 0 0 0 2l2 2m14-6l2 2a1.414 1.414 0 0 1 0 2l-2 2");
}

</style>
