<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b_wbmabzx"/><path class="topps6brl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:github-duotone" /></template>
<style>
.b_wbmabzx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 21v-3c0-1 0-2 1-3c-3 0-6-2-6-6c0-1.092.369-2.116 1-3a3.94 3.94 0 0 1 0-3s1.5 0 4 1c1.969-.5 4.031-.5 6 0c2.5-1 4-1 4-1a3.94 3.94 0 0 1 0 3c.631.884 1 1.908 1 3c0 4-3 6-6 6c1 1 1 2 1 3v3Z");
}

.ft5dv1b6b {
  fill: none;
}

.topps6brl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21v-3c0-1 0-2 1-3c-3 0-6-2-6-6c0-1.3.5-2.3 1-3q-.6-1.5 0-3s1.5 0 4 1q3-.75 6 0c2.5-1 4-1 4-1q.6 1.5 0 3c.5.7 1 1.7 1 3c0 4-3 6-6 6c1 1 1 2 1 3v3m-6-2c-4 1-4-3-6-3");
}

</style>
