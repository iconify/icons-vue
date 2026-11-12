<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d-3h37-ms"/><path class="zjfd1kaum"/><path class="byonj9b2c"/><path class="h4m9tpedx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-medicine-broken" /></template>
<style>
.byonj9b2c {
  d: path("M9 18H15");
}

.d-3h37-ms {
  d: path("M12 6L12 8M12 8L12 10M12 8H9.99998M12 8L14 8");
}

.h4m9tpedx {
  d: path("M3 14V10C3 6.22876 3 4.34315 4.17157 3.17157C5.34315 2 7.22876 2 11 2H13C16.7712 2 18.6569 2 19.8284 3.17157C20.4816 3.82476 20.7706 4.69989 20.8985 6M21 10V14C21 17.7712 21 19.6569 19.8284 20.8284C18.6569 22 16.7712 22 13 22H11C7.22876 22 5.34315 22 4.17157 20.8284C3.51839 20.1752 3.22937 19.3001 3.10149 18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zjfd1kaum {
  d: path("M8 14H9M12 14H16");
}

</style>
