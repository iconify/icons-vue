<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pvep1hbek"/><path class="yony_l-xz"/><path class="ok10udbbc"/><path class="vhlnnlb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-2-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ok10udbbc {
  d: path("M8.5 13L15.5 13");
}

.pvep1hbek {
  d: path("M2 2H22");
}

.vhlnnlb3x {
  d: path("M8.5 8L15.5 8");
}

.yony_l-xz {
  d: path("M4 2H20V12.2774C20 13.6175 20 14.2875 19.7319 14.8783C19.4638 15.4692 18.9595 15.9104 17.951 16.7929L15.951 18.5429C14.0685 20.1901 13.1272 21.0137 12 21.0137C10.8728 21.0137 9.93152 20.1901 8.04897 18.5429L6.04897 16.7928C5.04046 15.9104 4.5362 15.4692 4.2681 14.8783C4 14.2875 4 13.6175 4 12.2774V2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
