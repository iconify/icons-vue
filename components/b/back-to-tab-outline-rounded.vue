<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8hv6sbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:back-to-tab-outline-rounded" /></template>
<style>
.p8hv6sbco {
  fill: currentColor;
  d: path("M4 7.425V10q0 .425-.288.713T3 11t-.712-.288T2 10V5q0-.425.288-.712T3 4h5q.425 0 .713.288T9 5t-.288.713T8 6H5.4l3.575 3.575q.3.3.313.7t-.288.7t-.712.3t-.713-.3zM4 20q-.825 0-1.412-.587T2 18v-4q0-.425.288-.712T3 13t.713.288T4 14v4h7q.425 0 .713.288T12 19t-.288.713T11 20zm16.288-7.288Q20 12.425 20 12V6h-8q-.425 0-.712-.288T11 5t.288-.712T12 4h8q.825 0 1.413.588T22 6v6q0 .425-.288.713T21 13t-.712-.288M15 20q-.425 0-.712-.288T14 19v-3q0-.425.288-.712T15 15h6q.425 0 .713.288T22 16v3q0 .425-.288.713T21 20z");
}

</style>
