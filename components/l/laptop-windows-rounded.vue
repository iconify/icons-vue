<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzo7e0bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:laptop-windows-rounded" /></template>
<style>
.wzo7e0bsc {
  fill: currentColor;
  d: path("M1 20q-.425 0-.712-.288T0 19t.288-.712T1 18h3v-1q-.825 0-1.412-.587T2 15V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v10q0 .825-.587 1.413T20 17v1h3q.425 0 .713.288T24 19t-.288.713T23 20z");
}

</style>
