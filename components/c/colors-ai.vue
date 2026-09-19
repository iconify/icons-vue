<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ei6_l18li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:colors-ai" /></template>
<style>
.ei6_l18li {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-7.713 0l-1 37m.557-20.611l12.156.366M15.744 5.5l14.122 34.074m-9.694-23.392L11.351 42.5m4.733-14.121l9.276.322");
}

</style>
