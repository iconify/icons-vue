<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtokm889f"/><path class="tf4ep2o6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autodoc" /></template>
<style>
.tf4ep2o6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.787 28.532V42.5h-10.68v-8.99a3.02 3.02 0 0 0-3.022-3.02H5.5V19.467h13.713");
}

.vtokm889f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.894 5.5v8.99a3.02 3.02 0 0 0 3.02 3.02H42.5v11.022H22.234a3.02 3.02 0 0 1-3.021-3.021V5.5z");
}

</style>
