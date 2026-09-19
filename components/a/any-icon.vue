<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ack_csbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:any-icon" /></template>
<style>
.ack_csbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.722 5.5a8.226 8.226 0 0 1 8.222 8.222v8.222h-8.222A8.226 8.226 0 0 1 5.5 13.722h0A8.226 8.226 0 0 1 13.722 5.5m20.556 0a8.226 8.226 0 0 1 8.222 8.222h0a8.226 8.226 0 0 1-8.222 8.222h-8.222v-8.222A8.226 8.226 0 0 1 34.278 5.5M13.722 26.056h8.222v8.222a8.226 8.226 0 0 1-8.222 8.222h0A8.226 8.226 0 0 1 5.5 34.278h0a8.226 8.226 0 0 1 8.222-8.222m12.334 0h8.222a8.226 8.226 0 0 1 8.222 8.222h0a8.226 8.226 0 0 1-8.222 8.222h0a8.226 8.226 0 0 1-8.222-8.222z");
}

</style>
