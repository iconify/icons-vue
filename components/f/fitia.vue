<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4xbw4b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fitia" /></template>
<style>
.y4xbw4b8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.125 33.25a4.625 4.625 0 0 0 0 9.25h4.125a4.625 4.625 0 0 0 0-9.25zm0-13.875a4.625 4.625 0 0 0 0 9.25h16.5a4.625 4.625 0 0 0 0-9.25zm0-13.875a4.625 4.625 0 0 0 0 9.25h27.75a4.625 4.625 0 0 0 0-9.25z");
}

</style>
