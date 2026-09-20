<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6xaukkyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-schedule-outline-rounded" /></template>
<style>
.s6xaukkyz {
  fill: currentColor;
  d: path("M10.75 16.25L8.5 15.225q-.15-.075-.15-.225t.15-.225l2.25-1.025l1.025-2.25q.075-.15.225-.15t.225.15l1.025 2.25l2.25 1.025q.15.075.15.225t-.15.225l-2.25 1.025l-1.025 2.25q-.075.15-.225.15t-.225-.15l-1.025-2.25ZM5 22q-.825 0-1.413-.588T3 20V6q0-.825.588-1.413T5 4h1V3q0-.425.288-.713T7 2q.425 0 .713.288T8 3v1h8V3q0-.425.288-.713T17 2q.425 0 .713.288T18 3v1h1q.825 0 1.413.588T21 6v14q0 .825-.588 1.413T19 22H5Zm0-2h14V10H5v10ZM5 8h14V6H5v2Zm0 0V6v2Z");
}

</style>
