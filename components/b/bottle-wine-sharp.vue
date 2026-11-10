<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhm2rtb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-wine-sharp" /></template>
<style>
.uhm2rtb6o {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 14H11M18 16C19.657 16 21 14.657 21 13V10H15V13C15 14.657 16.343 16 18 16ZM18 16V22M14 22H22M5 2H9V7L11 10V22H3V10L5 7V2Z");
}

</style>
