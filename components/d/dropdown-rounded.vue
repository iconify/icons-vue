<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th83bisuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dropdown-rounded" /></template>
<style>
.th83bisuo {
  fill: currentColor;
  d: path("M12 13h5q.425 0 .713-.288T18 12V7q0-.425-.288-.712T17 6h-5q-.425 0-.712.288T11 7v5q0 .425.288.713T12 13m-7 8q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
