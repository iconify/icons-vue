<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thhkjetjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-6-outline-rounded" /></template>
<style>
.thhkjetjt {
  fill: currentColor;
  d: path("M11 17h2q.825 0 1.413-.587T15 15v-2q0-.825-.587-1.412T13 11h-2V9h2q.425 0 .713-.288T14 8t-.288-.712T13 7h-2q-.825 0-1.412.588T9 9v6q0 .825.588 1.413T11 17m0-4h2v2h-2zm-6 8q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
