<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="myh69jvxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:8tracks" /></template>
<style>
.myh69jvxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.917V14.75A9.25 9.25 0 1 1 33.25 24h-18.5A9.25 9.25 0 1 0 24 33.25v-6.167");
}

</style>
