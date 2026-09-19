<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x8bo6k2fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auxio-alt" /></template>
<style>
.x8bo6k2fq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.348 4.5h-4.64v22.613l.004.005a8.693 8.693 0 1 0 4.636 7.687v-21.61h8.695V4.5Z");
}

</style>
