<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r3g7vib_u"/><path class="mqn8vt71j"/><path class="o_qfmg2rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hospital-corridor" /></template>
<style>
.mqn8vt71j {
  fill: currentColor;
  d: path("M6 8.5h2v2h2v2H8v2H6v-2H4v-2h2Z");
}

.o_qfmg2rf {
  d: path("M12 11.5h7M16.5 9l2.5 2.5l-2.5 2.5");
}

.r3g7vib_u {
  d: path("M7 2.5V6m10-3.5V6M2.5 6h19v11h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
