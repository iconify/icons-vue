<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="px5xiwqdn"/><path class="s7-mgi2tv"/><circle class="shu3xdl9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-circle-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.px5xiwqdn {
  cx: 15px;
  cy: 9px;
  r: 2px;
}

.s7-mgi2tv {
  d: path("M20.0001 17.6001L17.7766 15.599C16.7371 14.6634 15.189 14.5702 14.0447 15.3744L13.7465 15.5839C12.9514 16.1428 11.8696 16.0491 11.1823 15.3618L6.89262 11.0721C6.03641 10.2159 4.66299 10.1702 3.75172 10.9675L2.28125 12.2542");
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

</style>
