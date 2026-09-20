<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drd3pd53z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cooking-rounded" /></template>
<style>
.drd3pd53z {
  fill: currentColor;
  d: path("M9.288 20.713Q9 20.425 9 20v-2H3q-.425 0-.712-.288T2 17t.288-.712T3 16h6q.825 0 1.413.588T11 18v2q0 .425-.288.713T10 21t-.712-.288m4 0Q13 20.426 13 20v-2q0-.825.588-1.412T15 16h6q.425 0 .713.288T22 17t-.288.713T21 18h-6v2q0 .425-.288.713T14 21t-.712-.288M6 15q-1.25 0-2.125-.875T3 12V9q0-.425.288-.712T4 8h16q.425 0 .713.288T21 9v3q0 1.25-.875 2.125T18 15zM4 7q-.425 0-.712-.288T3 6t.288-.712T4 5h5V4q0-.425.288-.712T10 3h4q.425 0 .713.288T15 4v1h5q.425 0 .713.288T21 6t-.288.713T20 7z");
}

</style>
