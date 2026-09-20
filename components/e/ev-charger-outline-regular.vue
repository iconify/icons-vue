<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="awt7oi67r"/><path class="wtf6_93on"/><path class="c3bjgh0gv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ev-charger-outline-regular" /></template>
<style>
.awt7oi67r {
  d: path("M4 21V5l3 -3h6l3 3v16Z");
}

.c3bjgh0gv {
  d: path("M16 9h3l2 2v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wtf6_93on {
  d: path("m13 6 -2.5 2.5H13L10.5 11");
}

</style>
