<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyiym1box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:adf-scanner-outline-rounded" /></template>
<style>
.xyiym1box {
  fill: currentColor;
  d: path("M2 18v-3q0-1.25.875-2.125T5 12h1V6q0-.825.588-1.412T8 4h8q.825 0 1.413.588T18 6v6h1q1.25 0 2.125.875T22 15v3q0 .825-.587 1.413T20 20H4q-.825 0-1.412-.587T2 18m6-6h8V6H8zm-4 6h16v-3q0-.425-.288-.712T19 14H5q-.425 0-.712.288T4 15zm14-1q.425 0 .713-.288T19 16t-.288-.712T18 15t-.712.288T17 16t.288.713T18 17M4 14h16z");
}

</style>
