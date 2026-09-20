<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyz9vdjpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-table-rounded" /></template>
<style>
.gyz9vdjpi {
  fill: currentColor;
  d: path("M3 8h18V5.5q0-.625-.437-1.062T19.5 4h-15q-.625 0-1.062.438T3 5.5zm0 6h18v-4H3zm1.5 6h15q.625 0 1.063-.437T21 18.5V16H3v2.5q0 .625.438 1.063T4.5 20M4.287 6.712Q4 6.425 4 6t.288-.712T5 5t.713.288T6 6t-.288.713T5 7t-.712-.288m0 6Q4 12.426 4 12t.288-.712T5 11t.713.288T6 12t-.288.713T5 13t-.712-.288m0 6Q4 18.426 4 18t.288-.712T5 17t.713.288T6 18t-.288.713T5 19t-.712-.288");
}

</style>
