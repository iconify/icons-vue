<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quliv-fyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-h4-outline-rounded" /></template>
<style>
.quliv-fyp {
  fill: currentColor;
  d: path("M3.759 16.356q-.143-.144-.143-.356V8q0-.213.143-.356q.144-.144.357-.144t.356.144t.144.356v3.5h5V8q0-.213.143-.356q.144-.144.357-.144t.356.144t.144.356v8q0 .213-.144.356t-.357.144t-.356-.144T9.616 16v-3.5h-5V16q0 .213-.145.356t-.356.144t-.356-.144m14 0q-.144-.144-.144-.356v-2.5h-4.192q-.343 0-.575-.232q-.232-.233-.232-.576V8q0-.213.143-.356q.144-.144.357-.144t.356.144t.144.356v4.5h4V8q0-.213.143-.356q.144-.144.357-.144t.356.144t.144.356v4.5h1.5q.212 0 .356.144t.144.357t-.144.356t-.356.143h-1.5V16q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
