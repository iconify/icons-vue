<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbrvtlcjq"/><path class="d6vmh5bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epic-games" /></template>
<style>
.d6vmh5bav {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.512 28h-4V12h4m19 5v-3a2 2 0 0 0-2-2h-1a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2v-3m-16 5V12h3a2 2 0 0 1 2 2v3.967a2 2 0 0 1-2.032 2l-2.968-.065M12.488 20h4m11.024-8v16");
}

.jbrvtlcjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 5.5h-25a4 4 0 0 0-4 4v25.747a2 2 0 0 0 1.128 1.8L24 44.5l15.373-7.453a2 2 0 0 0 1.127-1.8V9.5a4 4 0 0 0-4-4M17.925 38.298h12.15");
}

</style>
