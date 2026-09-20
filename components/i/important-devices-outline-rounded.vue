<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsb-954ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:important-devices-outline-rounded" /></template>
<style>
.dsb-954ca {
  fill: currentColor;
  d: path("M16.462 20q-.31 0-.54-.23t-.23-.54v-7.257q0-.31.23-.54t.54-.23h3.769q.31 0 .54.23q.229.23.229.54v7.258q0 .31-.23.54t-.54.229zm0-1.77h3.769v-5.257h-3.77zM8.654 20q-.213 0-.357-.143q-.143-.143-.143-.357t.143-.357t.357-.143H10.5v-3H4.616q-.672 0-1.144-.472T3 14.385v-8.77q0-.67.472-1.143Q3.944 4 4.616 4h12.769q.67 0 1.143.472q.472.472.472 1.144v3.088q0 .213-.143.357t-.357.143t-.357-.144T18 8.705V5.616q0-.27-.173-.443T17.385 5H4.615q-.269 0-.442.173T4 5.616v8.769q0 .269.173.442t.443.173h8.576q.214 0 .357.143t.143.357t-.143.357t-.357.143H11.5v3h1.846q.213 0 .357.143q.143.143.143.357t-.143.357t-.357.143zM11 11.616l1.373 1.101q.13.106.249.025t.069-.217l-.51-1.779l1.461-1.188q.106-.087.056-.22t-.186-.134h-1.766l-.554-1.646q-.05-.137-.192-.137t-.192.137l-.554 1.646H8.489q-.137 0-.187.134t.056.22l1.461 1.188l-.51 1.779q-.05.137.069.217q.118.081.249-.025zM11 10");
}

</style>
