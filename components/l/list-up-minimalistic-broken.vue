<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nmhvanepw"/><path class="f8edcu39k"/><path class="utbx9q75k"/><path class="pre11cbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-up-minimalistic-broken" /></template>
<style>
.f8edcu39k {
  d: path("M11 16H3");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmhvanepw {
  d: path("M20 11L3 11");
}

.pre11cbbs {
  d: path("M3 6L13.5 6M17.75 6L20 6");
}

.utbx9q75k {
  stroke-linejoin: round;
  d: path("M14 18L17.5 15L21 18");
}

</style>
