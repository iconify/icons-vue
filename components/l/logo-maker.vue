<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x54zyqh8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:logo-maker" /></template>
<style>
.x54zyqh8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 13.173V34.82h13.448M7.249 13.173V34.82m15.011.007V18.07l12.086 16.756M22.168 13.298l15.665 21.527m-4.999-6.869L43.5 13.298v21.527");
}

</style>
