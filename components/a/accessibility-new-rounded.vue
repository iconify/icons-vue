<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq5ha_62q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:accessibility-new-rounded" /></template>
<style>
.hq5ha_62q {
  fill: currentColor;
  d: path("M10.588 5.413Q10 4.825 10 4t.588-1.412T12 2t1.413.588T14 4t-.587 1.413T12 6t-1.412-.587M9 21V9q-1.225-.1-2.475-.275t-2.45-.45q-.425-.1-.687-.475T3.25 7t.525-.625t.85-.1q1.75.375 3.638.55T12 7t3.738-.175t3.637-.55q.45-.1.85.1T20.75 7t-.137.8t-.688.475q-1.2.275-2.45.45T15 9v12q0 .425-.287.713T14 22t-.712-.288T13 21v-5h-2v5q0 .425-.288.713T10 22t-.712-.288T9 21");
}

</style>
