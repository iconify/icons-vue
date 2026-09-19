<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="olz_pwbyz"/><path class="hzpqnlmob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:equate" /></template>
<style>
.hzpqnlmob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

.olz_pwbyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.07 32.207h9.353M14.069 13.5h9.354m-9.354 9.354h6.08M14.07 13.5v18.707m19.86-4.66a4.675 4.675 0 0 1-4.66 4.66h0a4.675 4.675 0 0 1-4.662-4.66v-3.03a4.675 4.675 0 0 1 4.661-4.661h0a4.675 4.675 0 0 1 4.662 4.66m0-4.66V38.5");
}

</style>
