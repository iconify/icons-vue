<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x66nfncgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calcolatrice-cas" /></template>
<style>
.x66nfncgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.48 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29.04a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4zm6 37v-37m13.429 12.598L20 29.902m8.909 0L20 18.098m12.097 8.381H38m-5.903-4.958H38");
}

</style>
