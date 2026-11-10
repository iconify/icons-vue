<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw9_s0b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hanger" /></template>
<style>
.gw9_s0b_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 7C7 4.79 8.7909 3 11 3C13.2091 3 15 4.79 15 7C15 8.61 13.5 10 12 11L11.5 11.5M11.6576 11.35L3.1428 20.15C2.8378 20.46 3.0538 21 3.4852 21H20.5149C20.9462 21 21.1622 20.46 20.8572 20.15L12.3424 11.35C12.1533 11.16 11.8467 11.16 11.6576 11.35Z");
}

</style>
