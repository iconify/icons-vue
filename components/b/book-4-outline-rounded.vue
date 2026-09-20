<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9xasp3xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:book-4-outline-rounded" /></template>
<style>
.y9xasp3xy {
  fill: currentColor;
  d: path("M6 22q-1.25 0-2.125-.875T3 19V5q0-1.25.875-2.125T6 2h9q.825 0 1.413.588T17 4v12q0 .825-.587 1.413T15 18H6q-.425 0-.712.288T5 19t.288.713T6 20h13V5q0-.425.288-.712T20 4t.713.288T21 5v15q0 .825-.587 1.413T19 22zm3-6h6V4H9zm-2 0V4H6q-.425 0-.712.288T5 5v11.175q.25-.075.488-.125T6 16zM5 4v12.175z");
}

</style>
