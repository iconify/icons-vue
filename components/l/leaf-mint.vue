<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk4wp1b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-mint" /></template>
<style>
.xk4wp1b9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.832 3.055l2.285 1.523a1.18 1.18 0 0 1 .508 1.172a1.4 1.4 0 0 0 .438 1.261l1.567 1.425a1.11 1.11 0 0 1 .245 1.314l-.055.11a1.5 1.5 0 0 0-.024 1.291l.581 1.278A1.06 1.06 0 0 1 18 13.75l-.394.262a1.5 1.5 0 0 0-.533.628l-.835 1.837a1.5 1.5 0 0 1-.765.753l-2.872 1.257a1.5 1.5 0 0 1-1.202 0L8.527 17.23a1.5 1.5 0 0 1-.765-.753l-.835-1.837a1.5 1.5 0 0 0-.533-.628L6 13.75a1.06 1.06 0 0 1-.377-1.321l.581-1.278A1.5 1.5 0 0 0 6.18 9.86l-.055-.11a1.11 1.11 0 0 1 .245-1.314l1.567-1.425a1.4 1.4 0 0 0 .438-1.261a1.18 1.18 0 0 1 .508-1.172l2.285-1.523a1.5 1.5 0 0 1 1.664 0M12 18.75v2.75m0-2.75V6.5");
}

</style>
