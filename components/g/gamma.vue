<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dz3f889ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gamma" /></template>
<style>
.dz3f889ly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.145 12.94V6.818H9.855a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h32.29V18.796h-18.19v5.59h9.096v12.777H17.833V12.94z");
}

</style>
