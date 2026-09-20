<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5uynlv6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:date-range" /></template>
<style>
.u5uynlv6m {
  fill: currentColor;
  d: path("M7.288 13.713Q7 13.425 7 13t.288-.712T8 12t.713.288T9 13t-.288.713T8 14t-.712-.288m4 0Q11 13.426 11 13t.288-.712T12 12t.713.288T13 13t-.288.713T12 14t-.712-.288m4 0Q15 13.426 15 13t.288-.712T16 12t.713.288T17 13t-.288.713T16 14t-.712-.288M5 22q-.825 0-1.412-.587T3 20V6q0-.825.588-1.412T5 4h1V2h2v2h8V2h2v2h1q.825 0 1.413.588T21 6v14q0 .825-.587 1.413T19 22zm0-2h14V10H5z");
}

</style>
