<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd9_-iz_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:audio-video-receiver-outline" /></template>
<style>
.pd9_-iz_d {
  fill: currentColor;
  d: path("M4 15h16V7H4zm1 4q-.425 0-.712-.288T4 18v-1q-.825 0-1.412-.587T2 15V7q0-.825.588-1.412T4 5h16q.825 0 1.413.588T22 7v8q0 .825-.587 1.413T20 17v1q0 .425-.288.713T19 19t-.712-.288T18 18v-1H6v1q0 .425-.288.713T5 19m-1-4V7zm13.913-2.588q.587-.587.587-1.412t-.587-1.412T16.5 9t-1.412.588T14.5 11t.588 1.413T16.5 13t1.413-.587M6 13h7V9H6z");
}

</style>
