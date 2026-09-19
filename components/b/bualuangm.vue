<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yfejcoo7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bualuangm" /></template>
<style>
.yfejcoo7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.315 19.476c-.712 5.58 8.876 12.83 10.685 16.092m10.685-16.092c.712 5.58-8.876 12.83-10.685 16.092V43.5c-6.483-5.657-20.911-10.134-11.257-23.656L24 4.5l11.257 15.344C44.911 33.366 30.482 37.843 24 43.5");
}

</style>
