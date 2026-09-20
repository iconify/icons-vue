<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u98c36bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-read-pause-rounded" /></template>
<style>
.u98c36bzf {
  fill: currentColor;
  d: path("M10.713 13.713Q11 13.425 11 13V7q0-.425-.288-.712T10 6t-.712.288T9 7v6q0 .425.288.713T10 14t.713-.288m4 0Q15 13.426 15 13V7q0-.425-.288-.712T14 6t-.712.288T13 7v6q0 .425.288.713T14 14t.713-.288M6 18l-2.3 2.3q-.475.475-1.088.213T2 19.575V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18z");
}

</style>
