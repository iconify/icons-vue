<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru0iglmqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fluid-balance-outline" /></template>
<style>
.ru0iglmqr {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6H4v12h8v2zm0-2V6zm15 5q-.825 0-1.412-.587T17 21v-1.1q-1.725-.35-2.863-1.713T13 15v-5q0-.825.575-1.412T15 8h6q.825 0 1.413.588T23 10v5q0 1.825-1.137 3.188T19 19.9V21h3v2zm.75-9H21v-4h-6v2h.75q.825 0 1.563.375T18.55 13.4q.2.3.525.45t.675.15M18 18q.975 0 1.75-.562T20.825 16H19.75q-.825 0-1.562-.363T16.95 14.6q-.225-.275-.537-.437T15.75 14H15v1q0 1.275.863 2.138T18 18M6 11h5V9H6zm0 4h5v-2H6z");
}

</style>
