<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j329bhr8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:block-puzzle" /></template>
<style>
.j329bhr8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 5.5H17.833v12.333h12.334zm12.333 0H30.167v12.333H42.5zm-24.667 0H5.5v12.333h12.333zm12.334 12.333H17.833v12.334h12.334zm0 12.334H17.833V42.5h12.334z");
}

</style>
