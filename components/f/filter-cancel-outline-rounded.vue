<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5-z5oblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-cancel-outline-rounded" /></template>
<style>
.c5-z5oblb {
  fill: currentColor;
  d: path("M18.025 17.4L16.6 18.825q-.3.3-.7.3t-.7-.3q-.275-.3-.275-.7t.275-.7L16.6 16l-1.4-1.425q-.275-.275-.275-.687t.275-.713q.3-.3.7-.3t.7.3l1.425 1.425l1.425-1.425q.3-.3.7-.3t.7.3q.275.3.275.7t-.275.7L19.45 16l1.4 1.425q.275.275.275.688t-.275.712q-.3.3-.7.3t-.7-.3zM9 20q-.425 0-.712-.288T8 19v-6L2.2 5.6q-.125-.125-.162-.287T2 5q0-.375.275-.687T3 4h14q.45 0 .725.313T18 5q0 .15-.038.313T17.8 5.6L12 13v6q0 .425-.288.713T11 20zm1-7.7L14.95 6h-9.9zm0 0");
}

</style>
