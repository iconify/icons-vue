<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mdcyymbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:levtech" /></template>
<style>
.mdcyymbfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 7.5L4.5 25L20 40.5zM10.864 31.364L43.5 7.5M11.799 21.725L20 40.5");
}

</style>
