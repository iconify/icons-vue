<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qc9gwfbaj"/><path class="xn4zvpbmt"/><path class="pyeja5bvq"/><path class="xj93a5bgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-2-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pyeja5bvq {
  d: path("M8 15.5H13.5");
}

.qc9gwfbaj {
  d: path("M18 6.00002V4.30604C18 3.08894 16.922 2.15402 15.7172 2.32614L4.91959 3.86865C4.39193 3.94403 4 4.39594 4 4.92895C4 5.52049 4.47953 6.00002 5.07107 6.00002H18Z");
}

.xj93a5bgo {
  d: path("M4 6V19C4 20.6569 5.34315 22 7 22H17C18.6569 22 20 20.6569 20 19V14M4 6V5M4 6H17C18.6569 6 20 7.34315 20 9V10");
}

.xn4zvpbmt {
  d: path("M8 12H16");
}

</style>
