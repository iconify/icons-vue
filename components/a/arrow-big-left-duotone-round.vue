<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q439mj5gp"/><path class="uosm7i6uf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-left-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q439mj5gp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 11v2a2 2 0 0 1-2 2h-4a2 2 0 0 0-2 2v1c0 .738-.631 1.369-1 1l-6-6a1.415 1.415 0 0 1 0-2l6-6c.369-.369 1 .262 1 1v1a2 2 0 0 0 2 2h4a2 2 0 0 1 2 2");
}

.uosm7i6uf {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12v-1a2 2 0 0 0-2-2h-4a2 2 0 0 1-2-2V6c0-.738-.631-1.369-1-1l-6 6a1.414 1.414 0 0 0 0 2l6 6c.369.369 1-.262 1-1v-1a2 2 0 0 1 2-2h4a2 2 0 0 0 2-2z");
}

</style>
