<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq8k5cb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-catch-up-24-regular" /></template>
<style>
.dq8k5cb5r {
  fill: currentColor;
  d: path("M18 20.5a.5.5 0 0 0 .5-.5V10H14a2 2 0 0 1-2-2V3.5H6a.5.5 0 0 0-.5.5v5.25a.75.75 0 0 1-1.5 0V4a2 2 0 0 1 2-2h6.172c.515 0 1.047.22 1.413.586l5.829 5.828A2 2 0 0 1 20 9.828V20a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-3.75a.75.75 0 0 1 1.5 0V20a.5.5 0 0 0 .5.5zm-.622-12L13.5 4.621V8a.5.5 0 0 0 .5.5zM2.75 13h2.505l1.557-3.551a.75.75 0 0 1 1.327-.091l.006.01l.05.103l2.413 6.027l1.427-2.1a.75.75 0 0 1 .545-.389l.01-.002l.107-.007h2a.75.75 0 0 1 .113 1.492l-.01.001l-.103.007h-1.554l-1.979 3.094a.75.75 0 0 1-1.306.04l-.005-.009l-.05-.101l-2.336-5.835l-1.035 2.362a.75.75 0 0 1-.564.439l-.012.002l-.11.008H2.75a.75.75 0 0 1-.113-1.492l.01-.001z");
}

</style>
