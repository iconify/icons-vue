<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="btpo_d5uv"/><path class="br8ipcc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:magicplan" /></template>
<style>
.br8ipcc4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 30.956v-8.662a5.25 5.25 0 1 0-10.5 0m21 8.662v-8.662a5.25 5.25 0 1 0-10.5 0m-10.5 8.662V17.044");
}

.btpo_d5uv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 42.5h6a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h6");
}

</style>
