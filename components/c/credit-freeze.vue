<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcxq1-b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:credit-freeze" /></template>
<style>
.hcxq1-b7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.1 17.5H2.5v-14h19v10M2.5 8h19M6 13h3m9.5 2.25v6.5m2.815-4.875l-5.63 3.25m5.63 0l-5.63-3.25");
}

</style>
