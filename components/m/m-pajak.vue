<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qmzth-byj"/><path class="tj3s-j1ef"/><path class="nx1i5obhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:m-pajak" /></template>
<style>
.nx1i5obhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.517a8.2 8.2 0 0 1 8.222 8.214v18.484h2.056a8.22 8.22 0 0 0 8.222-8.222V13.517a8 8 0 0 0-8-8z");
}

.qmzth-byj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.722 15.785A8.22 8.22 0 0 0 5.5 24.007v10.476a8 8 0 0 0 8 8H24a8.2 8.2 0 0 1-8.222-8.214V15.785z");
}

.tj3s-j1ef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24a8.2 8.2 0 0 1-8.222 8.215h-18.5v2.053a8.215 8.215 0 0 0 8.215 8.215H34.5a8 8 0 0 0 8-8zm-29-18.483a8 8 0 0 0-8 8V24a8.2 8.2 0 0 1 8.222-8.215h18.5v-2.054a8.215 8.215 0 0 0-8.215-8.214z");
}

</style>
