<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6qqg3o5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:11mp-sharp" /></template>
<style>
.k6qqg3o5t {
  fill: currentColor;
  d: path("M9.616 11.192h.884V5.808H8.116v.884h1.5zm5 0h.884V5.808h-2.384v.884h1.5zm-8.308 7h.884v-4.5h1.616v3h.884v-3h1.616v4.5h.884v-5.384H6.308zm7.5 0h.884v-1.5h3v-3.884h-3.884zm.884-2.384v-2.116h2.116v2.116zM4 20V4h16v16z");
}

</style>
