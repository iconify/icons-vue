<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oz8p7fbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fanqie-changting" /></template>
<style>
.oz8p7fbmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24m-23.183-9.788l-3.705 6.418m-2.51-6.838l-1.289 2.232m15.727-4.869l-9.307 16.119m11.94-9.41l-3.706 6.418m7.38-1.681l-1.289 2.232");
}

</style>
