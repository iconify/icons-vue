<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xa_506f5h"/><path class="nmhvanepw"/><path class="f8edcu39k"/><path class="utbx9q75k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-up-minimalistic-linear" /></template>
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

.utbx9q75k {
  stroke-linejoin: round;
  d: path("M14 18L17.5 15L21 18");
}

.xa_506f5h {
  d: path("M20 6L3 6");
}

</style>
