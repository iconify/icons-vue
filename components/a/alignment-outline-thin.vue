<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tw3a5bcpe"/><path class="lpthwr95f"/><path class="qlfruhq7c"/><path class="zpl29uvhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alignment-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpthwr95f {
  d: path("M3 17h6l4 -4");
}

.qlfruhq7c {
  d: path("M13 12h5");
}

.tw3a5bcpe {
  d: path("M3 7h6l4 4");
}

.zpl29uvhf {
  d: path("m16 9 3 3 -3 3");
}

</style>
