<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy0yvfjhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:faucet" /></template>
<style>
.sy0yvfjhh {
  fill: currentColor;
  d: path("M2 15v-2h5v-1H5q-.425 0-.712-.288T4 11t.288-.712T5 10h2q.825 0 1.413.588T9 12v1h2V6.1q0-1.725 1.2-2.912T15.125 2q1.15 0 2.125.6t1.5 1.65l1.15 2.3l-1.8.9l-1.15-2.3q-.275-.525-.775-.837T15.1 4q-.875 0-1.487.613T13 6.1V13h2v-1q0-.825.588-1.412T17 10h2q.425 0 .713.288T20 11t-.288.713T19 12h-2v1h5v2zm4 6q-.825 0-1.412-.587T4 19v-3h16v3q0 .825-.587 1.413T18 21z");
}

</style>
