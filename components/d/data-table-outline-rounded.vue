<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7-c7c0mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-table-outline-rounded" /></template>
<style>
.h7-c7c0mq {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zM5 8.325h14V5H5zm0 5.35h14v-3.35H5zM5 19h14v-3.325H5zM6.288 7.362Q6 7.075 6 6.65t.288-.712T7 5.65t.713.288T8 6.65t-.288.713T7 7.65t-.712-.288m0 5.35Q6 12.426 6 12t.288-.712T7 11t.713.288T8 12t-.288.713T7 13t-.712-.288m0 5.35Q6 17.776 6 17.35t.288-.712T7 16.35t.713.288t.287.712t-.288.713T7 18.35t-.712-.288");
}

</style>
