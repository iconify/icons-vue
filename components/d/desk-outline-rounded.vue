<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zij7v9wdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desk-outline-rounded" /></template>
<style>
.zij7v9wdv {
  fill: currentColor;
  d: path("M2 17V8q0-.825.588-1.412T4 6h16q.825 0 1.413.588T22 8v9q0 .425-.288.713T21 18t-.712-.288T20 17v-1h-4v1q0 .425-.288.713T15 18t-.712-.288T14 17V8H4v9q0 .425-.288.713T3 18t-.712-.288T2 17m14-7h4V8h-4zm0 4h4v-2h-4z");
}

</style>
