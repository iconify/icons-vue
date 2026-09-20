<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix8m80b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h4-rounded" /></template>
<style>
.ix8m80b2m {
  fill: currentColor;
  d: path("M3.643 16.356Q3.5 16.213 3.5 16V8q0-.213.144-.356t.357-.144t.356.144T4.5 8v3.5h5V8q0-.213.144-.356t.357-.144t.356.144T10.5 8v8q0 .213-.144.356t-.357.144t-.356-.144T9.5 16v-3.5h-5V16q0 .213-.144.356t-.357.144t-.356-.144m14 0Q17.5 16.213 17.5 16v-2.5h-4.192q-.344 0-.576-.232t-.232-.576V8q0-.213.144-.356t.357-.144t.356.144T13.5 8v4.5h4V8q0-.213.144-.356t.357-.144t.356.144T18.5 8v4.5H20q.213 0 .356.144t.144.357t-.144.356T20 13.5h-1.5V16q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
