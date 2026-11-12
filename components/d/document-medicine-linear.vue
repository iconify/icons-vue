<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bet-qjsfp"/><path class="d-3h37-ms"/><path class="oqzpqv97y"/><path class="byonj9b2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-medicine-linear" /></template>
<style>
.bet-qjsfp {
  d: path("M11 22H13C16.7712 22 18.6569 22 19.8284 20.8284C21 19.6569 21 17.7712 21 14V10C21 6.22876 21 4.34315 19.8284 3.17157C18.6569 2 16.7712 2 13 2H11C7.22876 2 5.34315 2 4.17157 3.17157C3 4.34315 3 6.22876 3 10V14C3 17.7712 3 19.6569 4.17157 20.8284C5.34315 22 7.22876 22 11 22Z");
}

.byonj9b2c {
  d: path("M9 18H15");
}

.d-3h37-ms {
  d: path("M12 6L12 8M12 8L12 10M12 8H9.99998M12 8L14 8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqzpqv97y {
  d: path("M8 14H16");
}

</style>
