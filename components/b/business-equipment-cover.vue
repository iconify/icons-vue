<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vhjiqkqwl"/><path class="wep-gobgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:business-equipment-cover" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhjiqkqwl {
  d: path("m8.731 3.72l.001-.005a1 1 0 0 1 .993-.903h.05a1 1 0 0 1 .993.903l.001.005a1.5 1.5 0 0 0 .919 1.243l.077.031a1.5 1.5 0 0 0 1.528-.228l.004-.004a1 1 0 0 1 1.341.065l.035.035a1 1 0 0 1 .065 1.341l-.004.004a1.5 1.5 0 0 0-.228 1.528l.031.077a1.5 1.5 0 0 0 1.243.919l.005.001a1 1 0 0 1 .903.993v.05a1 1 0 0 1-.903.993l-.005.001a1.5 1.5 0 0 0-1.243.919l-.031.077a1.5 1.5 0 0 0 .228 1.528l.004.004a1 1 0 0 1-.065 1.341l-.035.035a1 1 0 0 1-1.341.065l-.004-.004a1.5 1.5 0 0 0-1.528-.228l-.077.031a1.5 1.5 0 0 0-.919 1.243l-.001.005a1 1 0 0 1-.993.903h-.05a1 1 0 0 1-.993-.903l-.001-.005a1.5 1.5 0 0 0-.919-1.243l-.077-.031a1.5 1.5 0 0 0-1.528.228l-.004.004a1 1 0 0 1-1.341-.065l-.035-.035a1 1 0 0 1-.065-1.341l.004-.004a1.5 1.5 0 0 0 .228-1.528l-.031-.077a1.5 1.5 0 0 0-1.243-.919l-.005-.001a1 1 0 0 1-.903-.993v-.05a1 1 0 0 1 .903-.993l.005-.001a1.5 1.5 0 0 0 1.243-.919l.031-.077a1.5 1.5 0 0 0-.228-1.528l-.004-.004a1 1 0 0 1 .065-1.341l.035-.035a1 1 0 0 1 1.341-.065l.004.004a1.5 1.5 0 0 0 1.528.228l.077-.031a1.5 1.5 0 0 0 .919-1.243");
}

.wep-gobgp {
  d: path("M7.5 9.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m10.5 5L21 16v2.25c0 1.75-1.25 2.75-3 3.5c-1.75-.75-3-1.75-3-3.5V16Z");
}

</style>
