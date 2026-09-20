<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="taq_l6e3y"/><path class="qn3i6zboj"/><path class="ygpel9b0x"/><path class="ewesysbte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inner-join-duotone-thin" /></template>
<style>
.ewesysbte {
  d: path("M12 20.37a8.5 8.5 0 0 1 0 -16.74");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qn3i6zboj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 20.37a8.5 8.5 0 0 1 0 -16.74");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.taq_l6e3y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3.63a8.5 8.5 0 0 1 0 16.74");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ygpel9b0x {
  d: path("M12 3.63a8.5 8.5 0 0 1 0 16.74");
}

</style>
