<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyz2ch2fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:convolution" /></template>
<style>
.kyz2ch2fo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 18.25h4.816q.404 2.5 3.309 2.5h4.75q3.375 0 3.375-3.375v-4.75q0-2.905-2.5-3.309V4.5q0-2.75-2.75-2.75h-11q-1.139 0-1.945.805q-.805.806-.805 1.945v11q0 2.75 2.75 2.75m-1.25-5h3.5v3.5H4.5q-1.25 0-1.25-1.25zm5 0h1v3.5h-1zm1.066-1.5H8.25v-3.5h3.5v1.066q-2.095.339-2.434 2.434m-2.566 0h-3.5v-3.5h3.5zm0-8.5v3.5h-3.5V4.5q0-.518.366-.884T4.5 3.25zm5 0v3.5h-3.5v-3.5zm5 1.25v2.25h-3.5v-3.5h2.25q1.25 0 1.25 1.25m0 3.75v1h-3.5v-1z");
}

</style>
