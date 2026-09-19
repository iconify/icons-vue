<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ygisd9ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:luma" /></template>
<style>
.ygisd9ban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.219 13.852v20.346L24.06 44.499V3.5zM24.06 44.5l17.721-10.23l-17.72-10.231");
}

</style>
