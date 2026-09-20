<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0a3lu3za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h3-rounded" /></template>
<style>
.n0a3lu3za {
  fill: currentColor;
  d: path("M3.643 16.356Q3.5 16.213 3.5 16V8q0-.213.144-.356t.357-.144t.356.144T4.5 8v3.5h5V8q0-.213.144-.356t.357-.144t.356.144T10.5 8v8q0 .213-.144.356t-.357.144t-.356-.144T9.5 16v-3.5h-5V16q0 .213-.144.356t-.357.144t-.356-.144M13 16.5q-.213 0-.356-.144t-.144-.357t.144-.356T13 15.5h4.885q.269 0 .442-.173t.173-.442V12.5H15q-.213 0-.356-.144t-.144-.357t.144-.356T15 11.5h3.5V9.116q0-.27-.173-.443t-.442-.173H13q-.213 0-.356-.144t-.144-.357t.144-.356T13 7.5h4.885q.666 0 1.14.475t.475 1.14v5.77q0 .666-.475 1.14t-1.14.475z");
}

</style>
