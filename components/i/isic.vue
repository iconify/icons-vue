<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="e96l0m3fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:isic" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e96l0m3fo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.786 16.289v15.526m30.428-5.265a5.182 5.182 0 1 1-10.364 0v-5.183a5.16 5.16 0 0 1 5.182-5.182a5 5 0 0 1 4.99 5.183m-26.656 8.689a4.65 4.65 0 0 0 3.903 1.756h2.342a3.903 3.903 0 0 0 0-7.806h-2.537a3.903 3.903 0 0 1 0-7.805h2.342a4.19 4.19 0 0 1 3.903 1.756m3.363-1.757v15.612");
}

</style>
