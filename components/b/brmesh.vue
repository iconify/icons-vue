<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="brd43tbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brmesh" /></template>
<style>
.brd43tbaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 39.203c8.396-8.396 8.396-22.009 0-30.406s-22.009-8.396-30.406 0s-8.396 22.009 0 30.406l5.657-5.657c-5.272-5.272-5.272-13.82 0-19.092s13.82-5.272 19.092 0s5.272 13.82 0 19.092zm-22.804-3h15.203m-13.203 4h11.203m-9.203 4h7.203");
}

</style>
