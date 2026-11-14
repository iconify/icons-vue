<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf4x53k0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-balance-hidden" /></template>
<style>
.uf4x53k0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5v5M2.25 6.25l4.5 2.5m-4.5 0l4.5-2.5M12 5v5M9.75 6.25l4.5 2.5m-4.5 0l4.5-2.5M19.5 5v5m-2.25-3.75l4.5 2.5m-4.5 0l4.5-2.5M7 14.5c2.5 3 7.5 3 10 0M12 17v2.75m-3.25-3.5l-1.25 2m7.75-2l1.25 2");
}

</style>
