<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jjq2qh_fp"/><path class="l_xqm9bsu"/><path class="oqzpqv97y"/><path class="byonj9b2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-medicine-line-duotone" /></template>
<style>
.byonj9b2c {
  d: path("M9 18H15");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jjq2qh_fp {
  d: path("M3 10C3 6.22876 3 4.34315 4.17157 3.17157C5.34315 2 7.22876 2 11 2H13C16.7712 2 18.6569 2 19.8284 3.17157C21 4.34315 21 6.22876 21 10V14C21 17.7712 21 19.6569 19.8284 20.8284C18.6569 22 16.7712 22 13 22H11C7.22876 22 5.34315 22 4.17157 20.8284C3 19.6569 3 17.7712 3 14V10Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l_xqm9bsu {
  d: path("M12 6L12 8M12 8L12 10M12 8H10M12 8L14 8");
}

.oqzpqv97y {
  d: path("M8 14H16");
}

</style>
