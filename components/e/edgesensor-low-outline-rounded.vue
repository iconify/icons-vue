<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9wrzlbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edgesensor-low-outline-rounded" /></template>
<style>
.y9wrzlbxi {
  fill: currentColor;
  d: path("M8 21q-.825 0-1.412-.587T6 19V5q0-.825.588-1.412T8 3h8q.825 0 1.413.588T18 5v14q0 .825-.587 1.413T16 21zm8-2V5H8v14zM12.713 7.713Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288M3 13V8q0-.425.288-.712T4 7t.713.288T5 8v5q0 .425-.288.713T4 14t-.712-.288T3 13m16 3v-5q0-.425.288-.712T20 10t.713.288T21 11v5q0 .425-.288.713T20 17t-.712-.288T19 16M8 19V5z");
}

</style>
