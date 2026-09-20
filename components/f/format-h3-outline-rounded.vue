<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk1c-db7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h3-outline-rounded" /></template>
<style>
.qk1c-db7f {
  fill: currentColor;
  d: path("M4.143 16.356Q4 16.213 4 16V8q0-.213.144-.356t.357-.144t.356.144T5 8v3.5h5V8q0-.213.144-.356t.357-.144t.356.144T11 8v8q0 .213-.144.356t-.357.144t-.356-.144T10 16v-3.5H5V16q0 .213-.144.356t-.357.144t-.356-.144m9.357.144q-.213 0-.356-.144T13 15.999t.144-.356t.356-.143h4.885q.269 0 .442-.173t.173-.442V12.5h-3.5q-.213 0-.356-.144T15 11.999t.144-.356t.356-.143H19V9.116q0-.27-.173-.443t-.442-.173H13.5q-.213 0-.356-.144T13 7.999t.144-.356t.356-.143h4.885q.666 0 1.14.475T20 9.115v5.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
