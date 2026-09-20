<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh9w-acrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:kitchen-outline-rounded" /></template>
<style>
.uh9w-acrv {
  fill: currentColor;
  d: path("M8.288 7.713Q8 7.425 8 7V6q0-.425.288-.712T9 5t.713.288T10 6v1q0 .425-.288.713T9 8t-.712-.288m0 9Q8 16.426 8 16v-3q0-.425.288-.712T9 12t.713.288T10 13v3q0 .425-.288.713T9 17t-.712-.288M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm0-2h12v-9H6zM6 9h12V4H6z");
}

</style>
