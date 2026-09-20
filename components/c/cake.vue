<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1f7oibdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cake" /></template>
<style>
.p1f7oibdw {
  fill: currentColor;
  d: path("M4 22q-.425 0-.712-.288T3 21v-4q0-.825.588-1.412T5 15h14q.825 0 1.413.588T21 17v4q0 .425-.288.713T20 22zm1-9v-3q0-.825.588-1.412T7 8h4V6.55q-.45-.3-.725-.725T10 4.8q0-.375.15-.738t.45-.662L12 2l1.4 1.4q.3.3.45.662T14 4.8q0 .6-.275 1.025T13 6.55V8h4q.825 0 1.413.587T19 10v3z");
}

</style>
