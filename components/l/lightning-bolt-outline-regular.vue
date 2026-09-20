<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mbgtdkbsk"/><path class="flblq5ico"/><path class="zsil77j-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lightning-bolt-outline-regular" /></template>
<style>
.flblq5ico {
  d: path("m13 14 6 6");
}

.mbgtdkbsk {
  d: path("m16 2 -8 8h5l-8 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zsil77j-s {
  d: path("m19 14 -6 6");
}

</style>
