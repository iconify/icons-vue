<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h84ea8b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exa-uninstaller" /></template>
<style>
.h84ea8b6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.23 14.184h19.502v21.364a4 4 0 0 1-4.002 4.002H10.233a4 4 0 0 1-4.002-4.002zm6.127-5.734h7.244l1.92 1.593h5.814v4.141H4.5v-4.14h5.937zm17.288 9.355H43.5m-13.855 7.857h11.611M29.645 33.52h7.954");
}

</style>
