<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z77mre9ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daserste" /></template>
<style>
.z77mre9ce {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M39.57 5.5v29.73L19.78 42.5V21.32L8.43 25.5V17Z");
}

</style>
