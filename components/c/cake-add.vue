<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1d1w39nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cake-add" /></template>
<style>
.i1d1w39nz {
  fill: currentColor;
  d: path("M3 22q-.425 0-.712-.288T2 21v-4q0-.825.588-1.412T4 15h14q.825 0 1.413.588T20 17v4q0 .425-.288.713T19 22zm1-9v-3q0-.825.588-1.412T6 8h4V6.55q-.45-.3-.725-.725T9 4.8q0-.375.15-.738T9.6 3.4L11 2l1.4 1.4q.3.3.45.662T13 4.8q0 .6-.275 1.025T12 6.55V8h4q.825 0 1.413.587T18 10v3zm15-5V6h-2V4h2V2h2v2h2v2h-2v2z");
}

</style>
