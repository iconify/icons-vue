<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8bdlbb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:border-outer-rounded" /></template>
<style>
.d8bdlbb7t {
  fill: currentColor;
  d: path("M11.288 8.713Q11 8.425 11 8t.288-.712T12 7t.713.288T13 8t-.288.713T12 9t-.712-.288m-4 4Q7 12.426 7 12t.288-.712T8 11t.713.288T9 12t-.288.713T8 13t-.712-.288m4 0Q11 12.426 11 12t.288-.712T12 11t.713.288T13 12t-.288.713T12 13t-.712-.288m4 0Q15 12.426 15 12t.288-.712T16 11t.713.288T17 12t-.288.713T16 13t-.712-.288m-4 4Q11 16.426 11 16t.288-.712T12 15t.713.288T13 16t-.288.713T12 17t-.712-.288M5 19h14V5H5zm0 2q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
