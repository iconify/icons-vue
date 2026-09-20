<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4wjo4bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-4-rounded" /></template>
<style>
.p4wjo4bdw {
  fill: currentColor;
  d: path("M15 11v3q0 .425.288.713T16 15t.713-.288T17 14V6q0-.425-.288-.712T16 5t-.712.288T15 6v3h-2V6q0-.425-.288-.712T12 5t-.712.288T11 6v4q0 .425.288.713T12 11zm-7 7q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm-4 4q-.825 0-1.412-.587T2 20V7q0-.425.288-.712T3 6t.713.288T4 7v13h13q.425 0 .713.288T18 21t-.288.713T17 22z");
}

</style>
