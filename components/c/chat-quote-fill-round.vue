<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrfh5hbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-quote-fill-round" /></template>
<style>
.jrfh5hbub {
  fill: currentColor;
  d: path("M17 18H9c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5M10 7H8a1 1 0 0 0 0 2h1v.586l-1.707 1.707a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 11 10V8a1 1 0 0 0-1-1m6 0h-2a1 1 0 0 0 0 2h1v.586l-1.707 1.707a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 17 10V8a1 1 0 0 0-1-1");
}

</style>
