<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_bd1hphi"/><path class="g5gcnuhuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-boy" /></template>
<style>
.g5gcnuhuy {
  d: path("m10.618 7.059l2.764 1.382A.773.773 0 0 0 14.5 7.75a.773.773 0 0 0-1.118-.691l-2.764 1.382A.773.773 0 0 1 9.5 7.75a.773.773 0 0 1 1.118-.691M12 19.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_bd1hphi {
  d: path("M9 3c1 1.5 5 1.5 6 0l4.5 2.5L21 9l-3.5 1.25v4.25c0 2-1.5 3-3 3.5v3.5h-5V18c-1.5-.5-3-1.5-3-3.5v-4.25L3 9l1.5-3.5Z");
}

</style>
