<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5rs0c7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:blinds-2-closed-rounded" /></template>
<style>
.kq5rs0c7e {
  fill: currentColor;
  d: path("M5.55 20h12.9l-1.4-2H16v.5q0 .425-.287.713T15 19.5t-.712-.288T14 18.5V18H6.95zM16 10h2.45l-1.4-2H16zm0 5h2.45l-1.4-2H16zM5.55 15H14v-2H6.95zm0-5H14V8H6.95zM6 22q-.825 0-1.413-.587T4 20V8H3q-.425 0-.712-.288T2 7V5q0-1.25.875-2.125T5 2h14q1.25 0 2.125.875T22 5v2q0 .425-.288.713T21 8h-1v12q0 .825-.587 1.413T18 22z");
}

</style>
