<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zrwkhybyf"/><path class="s7eyaw7qq"/><path class="nzatmusii"/><path class="wg8_ddc1f"/><path class="zuuhu6bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dataset-split-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nzatmusii {
  d: path("M6 9h6");
}

.s7eyaw7qq {
  d: path("M15 4v16");
}

.wg8_ddc1f {
  d: path("M6 12h6");
}

.zrwkhybyf {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.zuuhu6bzg {
  d: path("M6 15h6");
}

</style>
