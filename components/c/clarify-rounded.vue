<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8kjy4lyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:clarify-rounded" /></template>
<style>
.w8kjy4lyg {
  fill: currentColor;
  d: path("M7 17h5q.425 0 .713-.288T13 16t-.288-.712T12 15H7q-.425 0-.712.288T6 16t.288.713T7 17m9.288-9.712Q16 7.575 16 8v8q0 .425.288.713T17 17t.713-.288T18 16V8q0-.425-.288-.712T17 7t-.712.288M7 13h5q.425 0 .713-.288T13 12t-.288-.712T12 11H7q-.425 0-.712.288T6 12t.288.713T7 13m0-4h5q.425 0 .713-.288T13 8t-.288-.712T12 7H7q-.425 0-.712.288T6 8t.288.713T7 9M4 21q-.825 0-1.412-.587T2 19V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v14q0 .825-.587 1.413T20 21z");
}

</style>
