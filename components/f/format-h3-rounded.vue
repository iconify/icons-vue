<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6qyqobpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-h3-rounded" /></template>
<style>
.r6qyqobpq {
  fill: currentColor;
  d: path("M3.288 16.713Q3 16.425 3 16V8q0-.425.288-.712T4 7t.713.288T5 8v3h4V8q0-.425.288-.712T10 7t.713.288T11 8v8q0 .425-.288.713T10 17t-.712-.288T9 16v-3H5v3q0 .425-.288.713T4 17t-.712-.288M14 17q-.425 0-.712-.288T13 16t.288-.712T14 15h5v-2h-3q-.425 0-.712-.288T15 12t.288-.712T16 11h3V9h-5q-.425 0-.712-.288T13 8t.288-.712T14 7h5q.825 0 1.413.588T21 9v6q0 .825-.587 1.413T19 17z");
}

</style>
