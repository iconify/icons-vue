<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fc7_88f7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:air-france" /></template>
<style>
.fc7_88f7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.268 19.09H43.5l-6.762 9.82h-8.202c3.352 0 8.732-9.82 8.732-9.82M22.348 24h6.668m-6.668 4.91v-9.82h10.259M17.43 25.657H7.067M4.5 28.91l7.748-9.82l7.748 9.82");
}

</style>
