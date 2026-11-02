<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rwv5ytb5v"/><path class="ug4u68bfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rwv5ytb5v {
  stroke-opacity: 0.4;
  d: path("m4 2l14 14");
}

.ug4u68bfi {
  d: path("M12 4h7a1 1 0 0 1 1 1v1l-3 3m-3 3v6l-4 2v-8L4 6V5a1 1 0 0 1 1-1h1");
}

</style>
