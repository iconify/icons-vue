<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1fhl3trp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-open-rounded" /></template>
<style>
.l1fhl3trp {
  fill: currentColor;
  d: path("M4 21q-.425 0-.712-.288T3 20t.288-.712T4 19h1V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v14h1q.425 0 .713.288T21 20t-.288.713T20 21zm13-2V5h-4.5V3.9q1.1.2 1.8 1.025T15 6.85v11.1q0 .725-.475 1.288t-1.2.687V19zm-6-6q.425 0 .713-.288T12 12t-.288-.712T11 11t-.712.288T10 12t.288.713T11 13");
}

</style>
