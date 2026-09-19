<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="izbzu7btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dprime" /></template>
<style>
.izbzu7btc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 41H19c-7.18 0-13-5.82-13-13c0-6.844 5.288-12.452 12-12.962V7h11c7.18 0 13 5.82 13 13c0 6.844-5.288 12.452-12.001 12.962z");
}

</style>
