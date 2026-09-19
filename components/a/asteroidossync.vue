<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tz4_-v1zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asteroidossync" /></template>
<style>
.tz4_-v1zs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5L44.5 24L24 44.5L3.5 24Zm-3.69 11.89l-4.1 4.1l4.1 4.1l4.1-4.1Zm4.1 4.1l4.1 4.1l-9 9l4.1 4.1l9-9l3.28-3.28l.82-.82l-8.2-8.2z");
}

</style>
