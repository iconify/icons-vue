<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2k4ipbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ausweisapp" /></template>
<style>
.j2k4ipbcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21 37.67a13.994 13.994 0 0 1 0-27.34V2.733a21.474 21.474 0 0 0 0 42.534Zm6-34.937v7.597a13.994 13.994 0 0 1 0 27.34v7.597a21.474 21.474 0 0 0 0-42.534");
}

</style>
