<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_6fp3hta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h1-rounded" /></template>
<style>
.t_6fp3hta {
  fill: currentColor;
  d: path("M5.643 16.356Q5.5 16.213 5.5 16V8q0-.213.144-.356t.357-.144t.356.144T6.5 8v3.5h5V8q0-.213.144-.356t.357-.144t.356.144T12.5 8v8q0 .213-.144.356t-.357.144t-.356-.144T11.5 16v-3.5h-5V16q0 .213-.144.356t-.357.144t-.356-.144m11 0Q16.5 16.213 16.5 16V8.5H15q-.213 0-.356-.144t-.144-.357t.144-.356T15 7.5h1.683q.357 0 .587.232t.23.576V16q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
