<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lbg8q3bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dictionary-com" /></template>
<style>
.lbg8q3bvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.147 41.354V14.77l-13.682-2.623l8.175 4.885v24.32H5.5V6.647h19.647A17.354 17.354 0 0 1 42.5 24a17.354 17.354 0 0 1-17.353 17.353");
}

</style>
