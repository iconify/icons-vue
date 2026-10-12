<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l3-xedcsc"/><path class="azua-3b0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:countdown-launch" /></template>
<style>
.azua-3b0i {
  d: path("M12 6c1.5 1.25 2.25 3 2.25 5v3.5h-4.5V11c0-2 .75-3.75 2.25-5m-2.25 6.5L8.25 14v2l1.5-.75m4.5-2.75l1.5 1.5v2l-1.5-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3-xedcsc {
  d: path("M12 2.75A9.25 9.25 0 1 1 2.75 12");
}

</style>
