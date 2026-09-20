<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrjswib9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:credit-score-outline-rounded" /></template>
<style>
.rrjswib9l {
  fill: currentColor;
  d: path("M4 8h16V6H4zM2 6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v5q0 .425-.288.713T21 12H4v6h3.1q.425 0 .713.288T8.1 19t-.288.713T7.1 20H4q-.825 0-1.412-.587T2 18zm2 0v12v-3.262v1.587zm10.95 15.6q-.2 0-.375-.075t-.325-.225l-2.85-2.85q-.275-.275-.288-.687t.288-.713q.275-.275.688-.275t.712.275l2.15 2.1l4.925-4.925q.3-.3.713-.287t.712.312q.275.3.288.7t-.288.7l-5.65 5.65q-.15.15-.325.225t-.375.075");
}

</style>
