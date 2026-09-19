<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uuzqvpbra"/><path class="inaooib1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daily-screen-time" /></template>
<style>
.inaooib1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.8v6.468l3.42 3.407");
}

.uuzqvpbra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.651 4.5h12.698a5.02 5.02 0 0 1 5.038 5.027v28.946a5.02 5.02 0 0 1-5.038 5.027H17.65a5.02 5.02 0 0 1-5.038-5.027V9.527A5.02 5.02 0 0 1 17.651 4.5M12.7 38.211h22.6");
}

</style>
