<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="haf9y2ejx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:auspost" /></template>
<style>
.haf9y2ejx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.753 31.973v13.41m0-42.765v2.474M16.296 3.93v40.143m5.457-38.98a13.514 13.514 0 1 1 0 26.88m0-29.354a21.5 21.5 0 1 1 0 42.764m-5.457-1.31a21.5 21.5 0 0 1 0-40.145");
}

</style>
