<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9dl54n7g"/><path class="aeubtm89r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fastdic" /></template>
<style>
.aeubtm89r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 4.544v13l-2.5-2l-2.5 2v-13m-16.77 29.11H39.6m-26.87 4.907H39.6");
}

.q9dl54n7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.73 4.5H10.4a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h2.33m0-39v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

</style>
