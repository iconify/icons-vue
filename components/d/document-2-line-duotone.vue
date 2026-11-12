<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="boxufibmx"/><path class="o1_eg2b-k"/><path class="qaiwobb2g"/><path class="qc9gwfbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-2-line-duotone" /></template>
<style>
.boxufibmx {
  d: path("M4 6V19C4 20.6569 5.34315 22 7 22H17C18.6569 22 20 20.6569 20 19V9C20 7.34315 18.6569 6 17 6H4ZM4 6V5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o1_eg2b-k {
  d: path("M8 12H16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qaiwobb2g {
  d: path("M8 15.5H13.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qc9gwfbaj {
  d: path("M18 6.00002V4.30604C18 3.08894 16.922 2.15402 15.7172 2.32614L4.91959 3.86865C4.39193 3.94403 4 4.39594 4 4.92895C4 5.52049 4.47953 6.00002 5.07107 6.00002H18Z");
}

</style>
