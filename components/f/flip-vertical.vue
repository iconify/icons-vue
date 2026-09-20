<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d41h0eb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flip-vertical" /></template>
<style>
.d41h0eb9c {
  fill: currentColor;
  d: path("M56 120h160a16 16 0 0 0 6.23-30.74l-.14-.06l-159.93-64A16 16 0 0 0 40 40v64a16 16 0 0 0 16 16m0-80l.15.06L216 104H56zm160 96H56a16 16 0 0 0-16 16v64a16 16 0 0 0 22.15 14.78l159.93-64l.14-.06A16 16 0 0 0 216 136M56.15 215.93L56 216v-64h160Z");
}

</style>
