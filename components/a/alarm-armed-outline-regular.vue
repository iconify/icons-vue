<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c2nlsybqj"/><path class="yea3zvbmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alarm-armed-outline-regular" /></template>
<style>
.c2nlsybqj {
  d: path("M12 3s4 2 8 3v6c0 5 -4 8 -8 9 -4 -1 -8 -4 -8 -9V6c4 -1 8 -3 8 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yea3zvbmx {
  d: path("m8 12 3 3 5 -5");
}

</style>
