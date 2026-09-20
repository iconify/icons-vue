<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jorh1p-8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fossify-musicplayer" /></template>
<style>
.jorh1p-8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.908 4.5a3.9 3.9 0 0 0-3.907 3.908v18.738a8.75 8.75 0 0 0-4.35-1.16a8.756 8.756 0 0 0-8.754 8.756a8.756 8.756 0 1 0 17.51 0a9 9 0 0 0-.007-.287l.014.023V13.299h4.782a3.9 3.9 0 0 0 3.907-3.908v-.983A3.9 3.9 0 0 0 33.196 4.5z");
}

</style>
