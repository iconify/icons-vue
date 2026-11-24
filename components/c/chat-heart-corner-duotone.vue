<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j6zzjccsj"/><path class="ge-xz8bnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-heart-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ge-xz8bnx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 17H8c-.64 0-1.36.36-2 1l-2 2c-.369.369-1-.262-1-1V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4m-4 7c-1-2-4-2-4 0s4 4 4 4s4-2 4-4s-3-2-4 0");
}

.j6zzjccsj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 9a2 2 0 0 0-2 2v6H8c-.763 0-1.479.48-2 1l-2 2c-.369.369-1-.262-1-1V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4Zm6 7c1-2 4-2 4 0s-4 4-4 4s-4-2-4-4s3-2 4 0");
}

</style>
