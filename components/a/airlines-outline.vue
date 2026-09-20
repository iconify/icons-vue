<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_3dnkbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airlines-outline" /></template>
<style>
.v_3dnkbwd {
  fill: currentColor;
  d: path("M5.8 18h11.55L19.6 6h-5.55zM2 20L13 4h9l-3 16zm12.5-6q1.05 0 1.775-.725T17 11.5t-.725-1.775T14.5 9t-1.775.725T12 11.5t.725 1.775T14.5 14m-8.7 4h11.55z");
}

</style>
