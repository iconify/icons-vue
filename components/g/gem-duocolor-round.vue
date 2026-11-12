<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h5nl8ib0a"/><path class="ye6p0-vub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-duocolor-round" /></template>
<style>
.h5nl8ib0a {
  stroke-opacity: 0.4;
  d: path("m8 9l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ye6p0-vub {
  d: path("m16.5 14l-3.162 3.513a1.8 1.8 0 0 1-2.676 0L4.27 10.41a2 2 0 0 1 .073-2.752l1.486-1.486A4 4 0 0 1 8.657 5h6.686a4 4 0 0 1 2.829 1.172l1.486 1.486a2 2 0 0 1 .073 2.752z");
}

</style>
