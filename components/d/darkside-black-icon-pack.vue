<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wyl76ccel"/><path class="nt4mwsupe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:darkside-black-icon-pack" /></template>
<style>
.nt4mwsupe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 18.127l11.48-1.652a3.29 3.29 0 0 1 3.759 3.256v16.055a3.89 3.89 0 0 1-3.338 3.853l-19.64 2.827a3.29 3.29 0 0 1-3.759-3.257l.018-7.684L24 29.873z");
}

.wyl76ccel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 29.873l-11.48 1.652a3.29 3.29 0 0 1-3.76-3.255V12.214a3.89 3.89 0 0 1 3.338-3.853l19.64-2.827a3.29 3.29 0 0 1 3.759 3.257v7.684L24 18.127z");
}

</style>
