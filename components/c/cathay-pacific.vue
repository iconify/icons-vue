<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p_kswy9sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cathay-pacific" /></template>
<style>
.p_kswy9sl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.744 42.5c12.178-4.112 23.083-8.298 29.345-12.759C24.11 27.017 13.245 20.784 8.192 5.5c-1.444 2.397 2.53 24.84 15.31 28.069z");
}

</style>
