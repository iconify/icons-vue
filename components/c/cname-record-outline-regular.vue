<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="ae-e09b3w"/><path class="rkhcgsbdl"/><path class="zbpm1d36f"/><path class="hrjweb57d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cname-record-outline-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.hrjweb57d {
  d: path("m9 15 3 -3 3 3");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.zbpm1d36f {
  d: path("m9 8 3 -3 3 3");
}

</style>
