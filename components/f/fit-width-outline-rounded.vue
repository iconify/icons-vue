<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erjtg98fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-width-outline-rounded" /></template>
<style>
.erjtg98fm {
  fill: currentColor;
  d: path("M3 20V4q0-.425.288-.712T4 3t.713.288T5 4v16q0 .425-.288.713T4 21t-.712-.288T3 20m16 0V4q0-.425.288-.712T20 3t.713.288T21 4v16q0 .425-.288.713T20 21t-.712-.288T19 20m-7.712-7.287Q11 12.425 11 12t.288-.712T12 11t.713.288T13 12t-.288.713T12 13t-.712-.288m-4 0Q7 12.426 7 12t.288-.712T8 11t.713.288T9 12t-.288.713T8 13t-.712-.288m8 0Q15 12.426 15 12t.288-.712T16 11t.713.288T17 12t-.288.713T16 13t-.712-.288");
}

</style>
