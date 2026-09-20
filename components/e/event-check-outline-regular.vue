<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v-jogvb5z"/><path class="l9-vpjbes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-check-outline-regular" /></template>
<style>
.l9-vpjbes {
  d: path("m13 14 2.5 2.5L20 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

</style>
