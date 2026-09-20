<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmlguy67x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flatware-rounded" /></template>
<style>
.dmlguy67x {
  fill: currentColor;
  d: path("M5.288 20.713Q5 20.425 5 20v-9q-.825 0-1.412-.587T3 9V3.7q0-.3.2-.5t.5-.2t.5.2t.2.5V7h.9V3.7q0-.3.2-.5T6 3t.5.2t.2.5V7h.9V3.7q0-.3.2-.5t.5-.2t.5.2t.2.5V9q0 .825-.587 1.413T7 11v9q0 .425-.288.713T6 21t-.712-.288m7 0Q12 20.426 12 20v-9.1q-1.05-.5-1.525-1.562T10 7.1q0-1.575.788-2.837T13 3t2.213 1.263T16 7.1q0 1.175-.475 2.238T14 10.9V20q0 .425-.288.713T13 21t-.712-.288m5 0Q17 20.426 17 20V4.175q0-.425.275-.712t.7-.288q1.125 0 2.075 1.2T21 7v5q0 .425-.288.713T20 13h-1v7q0 .425-.288.713T18 21t-.712-.288");
}

</style>
