<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wj6ylmbne"/><path class="i-2dnzb7m"/><path class="qw7b_6b1t"/><path class="z9owi-ayh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cocktail-outline-regular" /></template>
<style>
.i-2dnzb7m {
  d: path("M12 14v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.wj6ylmbne {
  d: path("M4 6h16l-8 8Z");
}

.z9owi-ayh {
  d: path("m15 8 4 -4");
}

</style>
