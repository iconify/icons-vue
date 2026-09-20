<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ialrik-em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:boy-outline-rounded" /></template>
<style>
.ialrik-em {
  fill: currentColor;
  d: path("M10.763 6.988q-.513-.513-.513-1.238t.513-1.237T12 4t1.238.513t.512 1.237t-.513 1.238T12 7.5t-1.237-.513M10 19v-4q-.425 0-.712-.288T9 14v-3.5q0-.825.588-1.412T11 8.5h2q.825 0 1.413.588T15 10.5V14q0 .425-.288.713T14 15v4q0 .425-.288.713T13 20h-2q-.425 0-.712-.288T10 19");
}

</style>
