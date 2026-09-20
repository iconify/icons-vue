<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0nle2bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-portrait-2-rounded" /></template>
<style>
.p0nle2bpc {
  fill: currentColor;
  d: path("M9 11h4q.425 0 .713-.288T14 10V7q0-.425-.288-.712T13 6H9q-.425 0-.712.288T8 7v3q0 .425.288.713T9 11m11 9q0 .825-.587 1.413T18 22H6q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4z");
}

</style>
