<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o1v68zbdu"/><path class="khaz4hblu"/><path class="xk6jv7b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fuel-pump-outline-regular" /></template>
<style>
.khaz4hblu {
  d: path("M6 7a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o1v68zbdu {
  d: path("M2.5 21V5l3 -3h7l3 3v16Z");
}

.xk6jv7b-l {
  d: path("M15 8h3l3 3v6");
}

</style>
