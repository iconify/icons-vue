<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuafeu31x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-fill-round" /></template>
<style>
.vuafeu31x {
  fill: currentColor;
  d: path("M3 19h1V8a5 5 0 0 1 5-5h3a1 1 0 0 1 1 1v5.223a5 5 0 0 1 4.123.995l1 .8A5 5 0 0 1 20 14.922V19h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m8-14H9a3 3 0 0 0-3 3v11h2v-4.078c0-1.518.69-2.955 1.877-3.904l1-.8l.123-.096Z");
}

</style>
