<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kttsq8-fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dolby" /></template>
<style>
.kttsq8-fl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.182 11.59H43.5v24.82h-5.318A12.41 12.41 0 0 1 25.772 24a12.41 12.41 0 0 1 12.41-12.41M9.818 36.41H4.5V11.59h5.318A12.41 12.41 0 0 1 22.227 24a12.41 12.41 0 0 1-12.41 12.41");
}

</style>
