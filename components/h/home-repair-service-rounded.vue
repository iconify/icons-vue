<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jealmacng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-repair-service-rounded" /></template>
<style>
.jealmacng {
  fill: currentColor;
  d: path("M9 8h6V6H9zM3 20q-.425 0-.712-.288T2 19v-4h4q0 .425.288.713T7 16t.713-.288T8 15h8q0 .425.288.713T17 16t.713-.288T18 15h4v4q0 .425-.288.713T21 20zm-1-6v-4q0-.825.588-1.412T4 8h3V6q0-.825.588-1.412T9 4h6q.825 0 1.413.588T17 6v2h3q.825 0 1.413.588T22 10v4h-4v-1q0-.425-.288-.712T17 12t-.712.288T16 13v1H8v-1q0-.425-.288-.712T7 12t-.712.288T6 13v1z");
}

</style>
