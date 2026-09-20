<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdv6pc05m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blinds-2" /></template>
<style>
.tdv6pc05m {
  fill: currentColor;
  d: path("M4 22V8H2V5q0-1.25.875-2.125T5 2h14q1.25 0 2.125.875T22 5v3h-2v14zm2-2h12v-3H6zm0-5h12v-3h-2v1q0 .425-.288.713T15 14t-.712-.288T14 13v-1H6zm0-5h8V8H6zm10 0h2V8h-2z");
}

</style>
