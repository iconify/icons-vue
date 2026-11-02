<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p27-ljoqn"/><path class="ji6b9qbdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ji6b9qbdp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V9c0-.738.631-1.369 1-1l3 3a1.414 1.414 0 0 1 0 2l-3 3c-.369.369-1-.262-1-1zm9-7v2m0 4v2m0 4v2m9-7V9c0-.738-.631-1.369-1-1l-3 3a1.414 1.414 0 0 0 0 2l3 3c.369.369 1-.262 1-1z");
}

.p27-ljoqn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 9c0-.898.572-1.928 1.521-2.089a1.34 1.34 0 0 1 1.186.382l3 3a2.414 2.414 0 0 1 0 3.414l-3 3a1.36 1.36 0 0 1-1.186.382C2.572 16.928 2 15.898 2 15Zm20 0v6c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-3-3a2.414 2.414 0 0 1 0-3.414l3-3a1.36 1.36 0 0 1 1.186-.382C21.428 7.072 22 8.102 22 9");
}

</style>
