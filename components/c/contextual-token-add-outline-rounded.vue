<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcqfolblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contextual-token-add-outline-rounded" /></template>
<style>
.xcqfolblg {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h9q.425 0 .713.288T14 5t-.288.713T13 6H4v12h16v-6q0-.425.288-.712T21 11t.713.288T22 12v6q0 .825-.587 1.413T20 20zm3-4h5q.425 0 .713-.288T13 15v-1q0-.425-.288-.712T12 13H7q-.425 0-.712.288T6 14v1q0 .425.288.713T7 16m0-5h5q.425 0 .713-.288T13 10V9q0-.425-.288-.712T12 8H7q-.425 0-.712.288T6 9v1q0 .425.288.713T7 11m9 5h1q.425 0 .713-.288T18 15v-3q0-.425-.288-.712T17 11h-1q-.425 0-.712.288T15 12v3q0 .425.288.713T16 16M4 18V6zM18 7h-1q-.425 0-.712-.288T16 6t.288-.712T17 5h1V4q0-.425.288-.712T19 3t.713.288T20 4v1h1q.425 0 .713.288T22 6t-.288.713T21 7h-1v1q0 .425-.288.713T19 9t-.712-.288T18 8z");
}

</style>
