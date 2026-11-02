<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i4ipbtb6x"/><path class="a3gf8y6yj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-to-go-duocolor" /></template>
<style>
.a3gf8y6yj {
  d: path("M6 7c-1 0-1.5-.2-1-1l1-2c.5-1 1-1 2-1h8c1 0 1.5 0 2 1l1 2c.5.8 0 1-1 1Zm0 0l1 12c.1 1.2.8 2 2 2h6c1.2 0 1.9-.8 2-2l1-12");
}

.i4ipbtb6x {
  stroke-opacity: 0.4;
  d: path("M7 12h10M7 16h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
