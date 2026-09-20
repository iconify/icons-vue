<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsh6zebbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blinds-outline-rounded" /></template>
<style>
.nsh6zebbk {
  fill: currentColor;
  d: path("M4 19V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v14h1q.425 0 .713.288T22 20t-.288.713T21 21H3q-.425 0-.712-.288T2 20t.288-.712T3 19zM6 7h8V5H6zm0 4h8V9H6zm0 8h12v-6h-2v1.825q.35.25.55.625t.2.8q0 .725-.513 1.238T15 18t-1.237-.513t-.513-1.237q0-.425.2-.8t.55-.625V13H6zM16 7h2V5h-2zm0 4h2V9h-2z");
}

</style>
