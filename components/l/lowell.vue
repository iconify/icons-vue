<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ewql2jefv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lowell" /></template>
<style>
.ewql2jefv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.854 36.188l-2.44-2.438L19.173 24l-9.759-9.75l4.88-4.875L28.93 24L14.294 38.625l4.88 4.875L38.586 24L19.173 4.5l-2.44 2.438");
}

</style>
