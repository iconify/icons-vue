<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tk_ecqynr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hiwatchpro" /></template>
<style>
.tk_ecqynr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.208 42.071L42.62 34.75v-21.5L29.207 5.083V32.75m-10.413-17.5v27.667L5.38 34.75v-21.5l13.413-7.32M29.208 24H18.794");
}

</style>
