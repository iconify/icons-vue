<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsv3_3bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-to-home-screen-rounded" /></template>
<style>
.fsv3_3bmb {
  fill: currentColor;
  d: path("M7 23q-.825 0-1.412-.587T5 21V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v3.1q.45.175.725.55T20 7.5v2q0 .475-.275.85T19 10.9V21q0 .825-.587 1.413T17 23zm6-10.6V14q0 .425.288.712T14 15t.713-.288T15 14v-4q0-.425-.288-.712T14 9h-4q-.425 0-.712.288T9 10t.288.713T10 11h1.6l-2.4 2.375q-.3.3-.3.713t.3.712t.713.3t.712-.3z");
}

</style>
