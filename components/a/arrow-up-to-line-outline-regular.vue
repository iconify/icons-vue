<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t46_l1b3y"/><path class="o8adkomvn"/><path class="bi-wyob_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-up-to-line-outline-regular" /></template>
<style>
.bi-wyob_j {
  d: path("m8 12 4 -4 4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8adkomvn {
  d: path("M12 8v12");
}

.t46_l1b3y {
  d: path("M7 4h10");
}

</style>
