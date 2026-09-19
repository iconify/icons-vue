<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i60ui7bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-ladder" /></template>
<style>
.i60ui7bsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.872 42.5l12-37m-1.743 37l11.999-37M23.674 9.191h10.257m-13.058 8.638H31.13m-5.602 17.274H15.27m2.802-8.637h10.257");
}

</style>
