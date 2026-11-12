<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x6v2ivbfo"/><path class="wwmhxmb7s"/><path class="hf2jg-64g"/><path class="ql78khb5l"/><path class="p_ni59b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:binoculars-linear" /></template>
<style>
.hf2jg-64g {
  d: path("M14 15H10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_ni59b0m {
  d: path("M14 9H10");
}

.ql78khb5l {
  d: path("M9.99986 19H1.9601M22.0397 19H14.0002");
}

.wwmhxmb7s {
  d: path("M17.0002 2H15.2665C14.162 2 14.0002 2.89543 14.0002 4V20C14.0002 21.1046 14.8956 22 16.0002 22H20.0002C21.1047 22 22.0002 21.1046 22.0002 20C22.0002 20 22.158 16.9462 22.0002 15C21.6403 10.5619 19.2306 5.22135 19.0002 4C18.7697 2.77865 18.5002 2 17.0002 2Z");
}

.x6v2ivbfo {
  d: path("M7.00007 2H8.73372C9.83829 2 10.0001 2.89543 10.0001 4V20C10.0001 21.1046 9.10464 22 8.00007 22H4.00007C2.8955 22 2.00007 21.1046 2.00007 20C2.00007 20 1.84226 16.9462 2.00007 15C2.35991 10.5619 4.7696 5.22135 5.00007 4C5.23053 2.77865 5.50007 2 7.00007 2Z");
}

</style>
