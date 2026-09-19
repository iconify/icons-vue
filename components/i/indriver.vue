<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vslr47eqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:indriver" /></template>
<style>
.vslr47eqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h8.954v8.954H5.5zm0 16.777h8.954v20.076H5.5zM24 33.399a9.472 9.472 0 0 0 0-18.945V5.5a18.5 18.5 0 0 1 0 37Z");
}

</style>
