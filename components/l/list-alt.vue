<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj1vxqqug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:list-alt" /></template>
<style>
.hj1vxqqug {
  fill: currentColor;
  d: path("M8.713 16.713Q9 16.425 9 16t-.288-.712T8 15t-.712.288T7 16t.288.713T8 17t.713-.288m0-4Q9 12.425 9 12t-.288-.712T8 11t-.712.288T7 12t.288.713T8 13t.713-.288m0-4Q9 8.426 9 8t-.288-.712T8 7t-.712.288T7 8t.288.713T8 9t.713-.288M11 17h6v-2h-6zm0-4h6v-2h-6zm0-4h6V7h-6zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
