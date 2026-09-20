<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ssl1sf5rz"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hutch-app" /></template>
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

.ssl1sf5rz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.163 23.989H38.5m0-3.21v6.441m-4.337-6.44v6.44m-18.241-6.44v4.307c0 1.177.97 2.13 2.166 2.13a2.15 2.15 0 0 0 2.174-2.13V20.78m11.917 4.28v.027c0 1.177-.971 2.13-2.166 2.13a2.15 2.15 0 0 1-2.175-2.13v-2.174c0-1.177.972-2.13 2.17-2.13c1.2 0 2.171.953 2.171 2.13v.026M9.5 23.985h4.337m0-3.205v6.44m-4.333-6.44v6.44m14.718 0v-6.44m-2.166 0h4.333");
}

</style>
