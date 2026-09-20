<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qolwfcbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:feedback-rounded" /></template>
<style>
.qolwfcbmt {
  fill: currentColor;
  d: path("m6 18l-2.3 2.3q-.475.475-1.088.213T2 19.575V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm6-3q.425 0 .713-.288T13 14t-.288-.712T12 13t-.712.288T11 14t.288.713T12 15m.713-4.288Q13 10.425 13 10V6q0-.425-.288-.712T12 5t-.712.288T11 6v4q0 .425.288.713T12 11t.713-.288");
}

</style>
