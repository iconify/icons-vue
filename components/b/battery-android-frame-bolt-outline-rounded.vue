<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uakvqobkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-frame-bolt-outline-rounded" /></template>
<style>
.uakvqobkq {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h11.45q.425 0 .713.288T16.45 7t-.288.713T15.45 8H4q-.425 0-.712.288T3 9v6q0 .425.288.713T4 16h10.45q.425 0 .713.288t.287.712t-.287.713t-.713.287zm0-4v-4q0-.425.288-.712T5 9h8.575q.65 0 .913.563t-.138 1.062l-2.9 3.625q-.275.35-.687.55T9.9 15H5q-.425 0-.712-.288T4 14m14.15 3.075q-.125.15-.312.075t-.138-.275L18.375 13H16.05q-.325 0-.462-.275t.062-.525l4.2-5.275q.125-.15.313-.075t.137.275L19.625 11h2.325q.325 0 .463.275t-.063.525z");
}

</style>
