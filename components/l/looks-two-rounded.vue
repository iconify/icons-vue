<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhsfyiu0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-two-rounded" /></template>
<style>
.mhsfyiu0g {
  fill: currentColor;
  d: path("M11 15v-2h2q.825 0 1.413-.587T15 11V9q0-.825-.587-1.412T13 7h-3q-.425 0-.712.288T9 8t.288.713T10 9h3v2h-2q-.825 0-1.412.588T9 13v3q0 .425.288.713T10 17h4q.425 0 .713-.288T15 16t-.288-.712T14 15zm-6 6q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
