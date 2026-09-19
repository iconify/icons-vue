<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gqngiwbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-chopsticks" /></template>
<style>
.gqngiwbph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.83 42.501L10.63 12.42a1.556 1.556 0 1 0-2.202 2.2zm2.199-1.191L19.727 6.21a1.558 1.558 0 0 0-2.615 1.69z");
}

</style>
