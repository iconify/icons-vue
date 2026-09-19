<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jsve3cxaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:betterment" /></template>
<style>
.jsve3cxaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.797 38.851c-8.396-8.396-8.396-22.008 0-30.405C17.193.05 30.806.05 39.203 8.446s8.396 22.009 0 30.405L24 30.15z");
}

</style>
