<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p3qamlbqg"/><path class="uqu_6uoth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handshake-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p3qamlbqg {
  stroke-opacity: 0.4;
  d: path("M3 4v12l3 3a2.121 2.121 0 1 0 3-3l2 2a2.121 2.121 0 1 0 3-3M3 5h7");
}

.uqu_6uoth {
  d: path("M10 5c2-2 5-2 7-1l2 1h2m0-1v8l-2 2m-9-9L7 8a2.121 2.121 0 1 0 3 3l1-1a2.83 2.83 0 0 1 4 0l4 4a2.121 2.121 0 1 1-3 3l-3-3");
}

</style>
