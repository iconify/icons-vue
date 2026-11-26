<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d-q-pxbuq"/><path clip-rule="evenodd" class="vj2xmxbtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-pen-sharp" /></template>
<style>
.d-q-pxbuq {
  d: path("M9.3842 21L3 21L3 3L21 3L21 9.5614M3 18L9 12L11.5738 14.5738M20.4142 15.6329L16.1715 19.8755L12.2189 20.9998L13.3431 17.0471L17.5858 12.8044C17.9609 12.4294 18.4696 12.2186 19 12.2186C20.1046 12.2186 21 13.1141 21 14.2186C21 14.7491 20.7893 15.2578 20.4142 15.6329Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vj2xmxbtx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5Z");
  stroke: none;
}

</style>
