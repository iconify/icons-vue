<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdvspd0rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-chart-rounded" /></template>
<style>
.hdvspd0rb {
  fill: currentColor;
  d: path("M8.713 16.713Q9 16.425 9 16v-5q0-.425-.288-.712T8 10t-.712.288T7 11v5q0 .425.288.713T8 17t.713-.288m4 0Q13 16.426 13 16V8q0-.425-.288-.712T12 7t-.712.288T11 8v8q0 .425.288.713T12 17t.713-.288m4 0Q17 16.426 17 16v-2q0-.425-.288-.712T16 13t-.712.288T15 14v2q0 .425.288.713T16 17t.713-.288m.574-8Q17 8.425 17 8V7h-1q-.425 0-.712-.288T15 6t.288-.712T16 5h1V4q0-.425.288-.712T18 3t.713.288T19 4v1h1q.425 0 .713.288T21 6t-.288.713T20 7h-1v1q0 .425-.288.713T18 9t-.712-.288M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h8q.425 0 .713.288T14 4v4q0 .825.588 1.413T16 10h4q.425 0 .713.288T21 11v8q0 .825-.587 1.413T19 21z");
}

</style>
