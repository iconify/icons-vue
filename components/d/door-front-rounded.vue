<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw3ajhb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-front-rounded" /></template>
<style>
.sw3ajhb_d {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h1V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v14h1q.425 0 .713.288T21 20t-.288.713T20 21zm10.713-8.287Q15 12.425 15 12t-.288-.712T14 11t-.712.288T13 12t.288.713T14 13t.713-.288");
}

</style>
