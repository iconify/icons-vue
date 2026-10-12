<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gn1iq53-h"/><path class="mbnc-bb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drip-irrigation" /></template>
<style>
.gn1iq53-h {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 4.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbnc-bb_c {
  d: path("M6.5 7.5V9M12 7.5V9m5.5-1.5V9M2.75 20.5h18.5M6.5 11c1.1 1.4 1.6 2.3 1.6 3a1.6 1.6 0 0 1-3.2 0c0-.7.5-1.6 1.6-3m5.5 0c1.1 1.4 1.6 2.3 1.6 3a1.6 1.6 0 0 1-3.2 0c0-.7.5-1.6 1.6-3m5.5 0c1.1 1.4 1.6 2.3 1.6 3a1.6 1.6 0 0 1-3.2 0c0-.7.5-1.6 1.6-3");
}

</style>
