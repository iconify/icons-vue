<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lhwv8jxtv"/><path class="s_4h7n_3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-out-of-service" /></template>
<style>
.lhwv8jxtv {
  d: path("M11.6 21.5H4v-19h16V12m0 9.5h0h-.6m-.4 0h-.6");
}

.s_4h7n_3a {
  d: path("M7 5h10v6H7Zm-.5 8.75h9m-8.75 3.5h.01m2.49 0h.01m2.49 0h.01m9.46-.847a2 2 0 1 1-1.623-1.623M15 21l2.75-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
