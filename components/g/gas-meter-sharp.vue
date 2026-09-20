<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv04ghbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:gas-meter-sharp" /></template>
<style>
.fv04ghbfy {
  fill: currentColor;
  d: path("M5 21V5h4.5V3h1v2h3V3h1v2H19v16zM8.5 9.5h7v-1h-7zm3.497 7.827q.822 0 1.394-.568q.57-.569.57-1.36q0-.635-.372-1.098q-.373-.462-1.589-1.878q-1.229 1.416-1.595 1.882q-.366.467-.366 1.089q0 .796.567 1.365q.568.568 1.39.568");
}

</style>
