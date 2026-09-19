<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-r29xa2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lifecounter" /></template>
<style>
.n-r29xa2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.084 38.461a4.694 4.694 0 0 1-4.693 4.694h0a4.694 4.694 0 0 1-4.694-4.694h0a4.694 4.694 0 0 1 4.694-4.693h0a4.694 4.694 0 0 1 4.693 4.693m-18.783 0a4.694 4.694 0 0 1-4.693 4.694h0a4.694 4.694 0 1 1 4.693-4.694m9.392-28.922a4.694 4.694 0 0 1-4.694 4.693h0a4.694 4.694 0 0 1-4.693-4.693h0a4.694 4.694 0 0 1 4.693-4.694h0a4.694 4.694 0 0 1 4.694 4.694M44 20.551a4.694 4.694 0 0 1-4.693 4.694h0a4.694 4.694 0 0 1-4.694-4.694h0a4.694 4.694 0 0 1 4.694-4.693h0A4.694 4.694 0 0 1 44 20.55m-30.613.001a4.694 4.694 0 1 1-9.387 0a4.694 4.694 0 0 1 9.387 0");
}

</style>
