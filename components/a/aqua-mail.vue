<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="d-obumi_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aqua-mail" /></template>
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

.d-obumi_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.986 40.303l12.203-9.238a3 3 0 0 1 3.622 0l12.2 9.243m-17-8.352L3.496 17.517m23.503 14.449L44.51 17.53m-7.84.417l-10.78 8.872a3.105 3.105 0 0 1-3.947-.002l-10.77-8.878c9.215-2.828 14.002 5.993 25.496.008");
}

</style>
