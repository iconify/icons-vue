<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bakl9un5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-5-outline-rounded" /></template>
<style>
.bakl9un5u {
  fill: currentColor;
  d: path("M13 17q.825 0 1.413-.587T15 15v-2q0-.825-.587-1.412T13 11h-2V9h3q.425 0 .713-.288T15 8t-.288-.712T14 7h-4q-.425 0-.712.288T9 8v4q0 .425.288.713T10 13h3v2h-3q-.425 0-.712.288T9 16t.288.713T10 17zm-8 4q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
