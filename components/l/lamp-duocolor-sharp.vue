<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qk7x1cc5y"/><path class="nno0zcbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lamp-duocolor-sharp" /></template>
<style>
.nno0zcbor {
  d: path("M9 3h6l4 8H5z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qk7x1cc5y {
  stroke-opacity: 0.4;
  d: path("M12 11v6m-4 0h8v4H8Z");
}

</style>
