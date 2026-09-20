<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su1389bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-saver-rounded" /></template>
<style>
.su1389bon {
  fill: currentColor;
  d: path("M16 19h-2q-.425 0-.712-.288T13 18t.288-.712T14 17h2v-2q0-.425.288-.712T17 14t.713.288T18 15v2h2q.425 0 .713.288T21 18t-.288.713T20 19h-2v2q0 .425-.288.713T17 22t-.712-.288T16 21zm-8 3q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V3q0-.425.288-.712T11 2h2q.425 0 .713.288T14 3v1h2q.425 0 .713.288T17 5v6.325q0 .275-.2.488t-.475.237q-1.05.125-1.95.563t-1.6 1.137q-.8.8-1.287 1.888T11 18q0 .75.175 1.45t.525 1.35q.2.425 0 .813t-.625.387z");
}

</style>
