<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-ihh_b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4g-mobiledata-outline-rounded" /></template>
<style>
.q-ihh_b6i {
  fill: currentColor;
  d: path("M7.288 16.713Q7 16.425 7 16v-2H4q-.425 0-.712-.288T3 13V8q0-.425.288-.712T4 7t.713.288T5 8v4h2V8q0-.425.288-.712T8 7t.713.288T9 8v4h1q.425 0 .713.288T11 13t-.288.713T10 14H9v2q0 .425-.288.713T8 17t-.712-.288M14 17q-.825 0-1.412-.587T12 15V9q0-.825.588-1.412T14 7h6q.425 0 .713.288T21 8t-.288.713T20 9h-6v6h5v-2h-1.5q-.425 0-.712-.288T16.5 12t.288-.712T17.5 11H20q.425 0 .713.288T21 12v3q0 .825-.587 1.413T19 17z");
}

</style>
