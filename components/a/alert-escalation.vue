<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9if3zbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alert-escalation" /></template>
<style>
.n9if3zbcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.595 19.5H2.5l9-16.5l5.028 9.218M11.5 9v4m0 3.25h.01M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
