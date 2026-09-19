<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ap_x9rb1v"/><path class="nlec6pb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:g-mon-pro" /></template>
<style>
.ap_x9rb1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 5.625l9.093 5.25v10.5L24 26.625l-9.093-5.25v-10.5z");
}

.nlec6pb0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.093 21.375l9.093 5.25v10.5l-9.093 5.25L24 37.125v-10.5m0 10.5l-9.093 5.25l-9.093-5.25v-10.5l9.093-5.25");
}

</style>
