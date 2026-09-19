<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hicn2acny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anycubic" /></template>
<style>
.hicn2acny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.724 23.136l-10.213-1.1M15.96 6.062l16.55 16.079l-15.712 19.902M15.594 5.695L4.962 24.498L16.59 42.304l14.14-5.184l12.308-13.93l-13.46-12.152z");
}

</style>
