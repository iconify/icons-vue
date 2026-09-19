<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fj_5k4h5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:atomic-mail" /></template>
<style>
.fj_5k4h5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.906v13.438m-9.406 6.718L24 25.345m10.75-8.063L24 25.344M13.25 17.28L24 25.344m0 0l9.406 6.719c5.375 3.359 12.094 0 12.094-8.063c0-11.879-9.621-21.5-21.5-21.5S2.5 12.121 2.5 24S12.121 45.5 24 45.5c6.719 0 12.094-2.687 14.781-6.719");
}

</style>
