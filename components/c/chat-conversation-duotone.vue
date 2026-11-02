<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="keovx8nim"/><path class="nc30oob_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-conversation-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.keovx8nim {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 5a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 16.928 2 15.898 2 15Z");
}

.nc30oob_x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10V5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H8c-.64 0-1.36.36-2 1l-2 2c-.369.369-1-.262-1-1zm16-1a2 2 0 0 1 2 2v8c0 .738-.631 1.369-1 1l-2-2c-.64-.64-1.36-1-2-1H9");
}

</style>
