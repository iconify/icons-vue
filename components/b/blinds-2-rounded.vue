<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov4u-ubax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blinds-2-rounded" /></template>
<style>
.ov4u-ubax {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V8H3q-.425 0-.712-.288T2 7V5q0-1.25.875-2.125T5 2h14q1.25 0 2.125.875T22 5v2q0 .425-.288.713T21 8h-1v12q0 .825-.587 1.413T18 22zm0-2h12v-3H6zm0-5h12v-3h-2v1q0 .425-.288.713T15 14t-.712-.288T14 13v-1H6zm0-5h8V8H6zm10 0h2V8h-2z");
}

</style>
