<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk81fvbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:attachment-rounded" /></template>
<style>
.mk81fvbqy {
  fill: currentColor;
  d: path("M8.462 17.173q-2.273 0-3.867-1.565Q3 14.042 3 11.778Q3 9.517 4.595 7.94t3.867-1.575h8.73q1.587 0 2.698 1.092Q21 8.548 21 10.135t-1.11 2.678q-1.111 1.09-2.698 1.09H8.923q-.88 0-1.517-.614t-.637-1.498t.627-1.52t1.527-.636h7.808q.212 0 .356.144t.144.356t-.144.356t-.356.144H8.923q-.479 0-.816.327t-.338.807t.338.807t.816.328h8.289q1.165-.006 1.977-.805T20 10.136t-.821-1.967t-1.987-.804h-8.73Q6.608 7.36 5.304 8.649T4 11.786q0 1.823 1.305 3.1t3.157 1.287h8.269q.212 0 .356.144t.144.357t-.144.356t-.356.143z");
}

</style>
