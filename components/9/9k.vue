<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsm5rh15q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:9k" /></template>
<style>
.xsm5rh15q {
  fill: currentColor;
  d: path("M6.5 15H10q.425 0 .713-.288T11 14v-4q0-.425-.288-.712T10 9H7.5q-.425 0-.712.288T6.5 10v1.5q0 .425.288.713t.712.287h2v1h-3zM8 11.5V10h1.5v1.5zm5 3.5h1.5v-2.25L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13zm-8 6q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
