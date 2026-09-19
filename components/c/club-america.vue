<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="p-o8v9z-u"/><path class="a73vasbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:club-america" /></template>
<style>
.a73vasbwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.767 26.126a4.35 4.35 0 0 1-4.325 4.374h-.024h0a4.35 4.35 0 0 1-4.35-4.35h0v-4.3a4.35 4.35 0 0 1 4.35-4.35h0a4.35 4.35 0 0 1 4.35 4.35v.024m14.477 8.578l4.384-12.942m4.199 12.98l-4.199-12.98m2.796 8.639h-5.723M13.738 13.741l-.958 2M8.793 9.004l4.945 4.737L24 10.146l10.263 3.595l4.944-4.737M35.22 15.74l-.958-1.999m.001 20.518l.957-2m3.987 6.737l-4.945-4.737L24 37.854l-10.262-3.595l-4.945 4.737m3.987-6.736l.958 1.999");
}

.p-o8v9z-u {
  cx: 24.073px;
  cy: 24.023px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
