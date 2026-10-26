<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vum8rabko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-taxi-front-off-sharp" /></template>
<style>
.vum8rabko {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 20L3 20L3 12L12 12M5.0513 12L5.3518 11L6 6M18 20L19 20L19 22L18 22L18 20ZM5 20L6 20L6 22L5 22L5 20ZM5.3518 11L2.5 11M6 16L9 16M16.6569 12L21 12L21 16.3431M10.6569 6L18 6L18.6482 11L18.9487 12M9.1145 4.9735L10.5 2L13.5 2L15.3638 6M18.6482 11L21.5 11M1.7071 1.7071L22.2929 22.2929");
}

</style>
