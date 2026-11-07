<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3erqrbye"/><path class="bsyq0zp1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-duocolor-sharp" /></template>
<style>
.bsyq0zp1v {
  d: path("M21 13v6H3V5h8M3 5l6 6h4");
}

.n3erqrbye {
  stroke-opacity: 0.4;
  d: path("m15 6l2 2l4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
