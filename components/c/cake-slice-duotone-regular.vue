<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ftphci-zo"/><path class="nocp8rbgi"/><path class="ykj7ebbjl"/><path class="oqj-o0b2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cake-slice-duotone-regular" /></template>
<style>
.ftphci-zo {
  fill: currentColor;
  d: path("M5 20v-8l6 -6h8v14Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nocp8rbgi {
  d: path("M5 20v-8l6 -6h8v14Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqj-o0b2r {
  d: path("M5 14h14");
}

.ykj7ebbjl {
  d: path("M7 10h12");
}

</style>
