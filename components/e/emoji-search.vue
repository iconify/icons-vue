<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="biaxtsbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-search" /></template>
<style>
.biaxtsbrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.607 5.5c7.772 0 14.045 6.304 14.045 14.107a14.026 14.026 0 0 1-14.045 14.045C11.804 33.652 5.5 27.38 5.5 19.607A14.09 14.09 0 0 1 19.607 5.5m9.923 24.03L42.5 42.5");
}

</style>
