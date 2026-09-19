<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sdmg2cb0k"/><path class="a3d-130tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flamingo" /></template>
<style>
.a3d-130tt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5V24l16.021 9.25m0-18.5L24 24V5.5M7.978 14.75L24 24L7.978 33.25");
}

.sdmg2cb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.978 14.75v18.5L24 42.5l16.021-9.25v-18.5L24 5.5z");
}

</style>
