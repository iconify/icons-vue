<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7n27nx6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-align-left-outline-rounded" /></template>
<style>
.e7n27nx6w {
  fill: currentColor;
  d: path("M3.288 19.713Q3 19.425 3 19V5q0-.425.288-.712T4 4t.713.288T5 5v14q0 .425-.288.713T4 20t-.712-.288M10.8 13l1.9 1.9q.275.275.275.7t-.275.7t-.7.275t-.7-.275l-3.6-3.6q-.15-.15-.213-.325T7.426 12t.063-.375t.212-.325l3.6-3.6q.275-.275.7-.275t.7.275t.275.7t-.275.7L10.8 11H20q.425 0 .713.288T21 12t-.288.713T20 13z");
}

</style>
