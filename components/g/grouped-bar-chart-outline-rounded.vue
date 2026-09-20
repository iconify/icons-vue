<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxafj3b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grouped-bar-chart-outline-rounded" /></template>
<style>
.yxafj3b9l {
  fill: currentColor;
  d: path("M5 20q-.425 0-.712-.288T4 19V9q0-.425.288-.712T5 8h2q.425 0 .713.288T8 9v10q0 .425-.288.713T7 20zm5 0q-.425 0-.712-.288T9 19v-5q0-.425.288-.712T10 13h2q.425 0 .713.288T13 14v5q0 .425-.288.713T12 20zm7 0q-.425 0-.712-.288T16 19V5q0-.425.288-.712T17 4h2q.425 0 .713.288T20 5v14q0 .425-.288.713T19 20z");
}

</style>
