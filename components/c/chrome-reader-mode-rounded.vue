<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjz3ybcja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-reader-mode-rounded" /></template>
<style>
.kjz3ybcja {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm9-2h7V6h-7zm5.25-3q.325 0 .538-.213T19 14.25t-.213-.537t-.537-.213h-3.5q-.325 0-.537.213T14 14.25t.213.538t.537.212zm0-2.5q.325 0 .538-.213T19 11.75t-.213-.537T18.25 11h-3.5q-.325 0-.537.213T14 11.75t.213.538t.537.212zm0-2.5q.325 0 .538-.213T19 9.25t-.213-.537t-.537-.213h-3.5q-.325 0-.537.213T14 9.25t.213.538t.537.212z");
}

</style>
