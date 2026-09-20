<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gg6w4tm7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brackeyside" /></template>
<style>
.gg6w4tm7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.11 20.42l-4.52-4.51L3.5 24L24 44.5l8.09-8.09l-4.51-4.52L24 35.47L12.53 24zm15.78 7.16l4.52 4.51L44.5 24L24 3.5l-8.09 8.09l4.51 4.52L24 12.53L35.47 24z");
}

</style>
