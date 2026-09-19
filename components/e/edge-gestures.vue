<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bbwroj02y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edge-gestures" /></template>
<style>
.bbwroj02y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.192 42.387l6.167.057V5.5H7.193m33.616.113l-6.168-.057V42.5h6.168");
}

</style>
