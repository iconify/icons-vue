<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qyak8fvti"/><path class="gxu9yrb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:easel-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gxu9yrb2v {
  d: path("M1 16L23 16M8 16L6.2862 21.7127M16 16L17.7138 21.7127M12 16L12 20");
}

.qyak8fvti {
  fill: currentColor;
  d: path("M4 2L20 2C20.5523 2 21 2.4477 21 3L21 16C21 16.5523 20.5523 17 20 17L4 17C3.4477 17 3 16.5523 3 16L3 3C3 2.4477 3.4477 2 4 2Z");
  stroke: none;
}

</style>
