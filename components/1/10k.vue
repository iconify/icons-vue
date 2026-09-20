<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy3jy_bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:10k" /></template>
<style>
.hy3jy_bxs {
  fill: currentColor;
  d: path("M6 15h1.5V9H5v1.5h1zm3.5 0H12q.425 0 .713-.288T13 14v-4q0-.425-.288-.712T12 9H9.5q-.425 0-.712.288T8.5 10v4q0 .425.288.713T9.5 15m.5-1.5v-3h1.5v3zm4 1.5h1.5v-2.25L17.25 15H19l-2.25-3L19 9h-1.75l-1.75 2.25V9H14zm-9 6q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
