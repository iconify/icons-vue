<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dter5fhtk"/><path class="m3d5oybbj"/><path class="w4qd-obeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flight-dark" /></template>
<style>
.dter5fhtk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.323 43.5c-1.496-13.364 24.575-15.476 23.432-26.41c10.44 17.61-23.26 14.153-23.432 26.41");
}

.m3d5oybbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.323 43.5C1.86 31.302 34.575 15.158 27.44 4.5c19.586 15.043-22.994 25.985-15.117 39");
}

.w4qd-obeu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.323 43.5c3.51-6.658 27.137-.619 23.096-12.981c-3.02 9.608-17.693 2.261-23.096 12.981");
}

</style>
