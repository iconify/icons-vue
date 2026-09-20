<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usc1s7bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:21mp-sharp" /></template>
<style>
.usc1s7bta {
  fill: currentColor;
  d: path("M7.808 11.192h3.884v-.884h-3V8.885h3V5.808H7.808v.884h3v1.424h-3zm7 0h.884V5.808h-2.384v.884h1.5zm-8.5 7h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884v-5.384H6.308zm7.5 0h.884v-1.5h3v-3.884h-3.884zm.884-2.384v-2.116h2.116v2.116zM4 20V4h16v16z");
}

</style>
