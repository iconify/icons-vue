<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_hupybaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:building-complex-sharp" /></template>
<style>
.n_hupybaq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21L4 21L4 15M9 21L13.5 21M9 5.9167L16 3.8333L19.1313 2.9635M16 11L22 11L22 21L17.5 21M1.2852 8.2127L4 7.4048L9 5.9167M4 15L4 7.4048M9 21L9 5.9167M16 3.8333L16 11M16 11L9 11M9 15L4 15M13.5 21L13.5 16L17.5 16L17.5 21M13.5 21L17.5 21");
}

</style>
