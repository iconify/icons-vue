<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="osbn6ha0r"/><path class="ciwekkant"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:journal" /></template>
<style>
.ciwekkant {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.55 38.547A6.15 6.15 0 0 1 32.8 42.5H11.673A6.17 6.17 0 0 1 5.5 36.326V15.2c0-2.63 1.64-4.865 3.953-5.75m27.376-3.93v13.213l-4.226-3.948l-4.225 3.948V5.5");
}

.osbn6ha0r {
  width: 33.47px;
  height: 33.47px;
  x: 9.03px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.171px;
  ry: 6.171px;
}

</style>
