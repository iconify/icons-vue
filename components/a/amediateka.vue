<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y09pvht5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amediateka" /></template>
<style>
.y09pvht5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.91 12.867L4.5 39.465m18.405-28.76L8.406 39.466m19.5-30.932L12.312 39.466h6.677l1.983-3.924H34.84l1.985 3.924H43.5zm0 13.297l4.477 8.851h-8.954z");
}

</style>
