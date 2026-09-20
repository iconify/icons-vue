<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-lfo6b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:explicit-rounded" /></template>
<style>
.h-lfo6b4c {
  fill: currentColor;
  d: path("M11 15v-2h3q.425 0 .713-.288T15 12t-.288-.712T14 11h-3V9h3q.425 0 .713-.288T15 8t-.288-.712T14 7h-4q-.425 0-.712.288T9 8v8q0 .425.288.713T10 17h4q.425 0 .713-.288T15 16t-.288-.712T14 15zm-6 6q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
