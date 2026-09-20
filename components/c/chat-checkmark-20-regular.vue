<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ytmym8bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-20-regular" /></template>
<style>
.ytmym8bbr {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1-3.613 15.14l-.121-.065l-3.645.91a.5.5 0 0 1-.62-.441v-.081l.014-.084l.91-3.644l-.064-.12a8 8 0 0 1-.828-2.886l-.025-.382L2 10a8 8 0 0 1 8-8m0 1a7 7 0 0 0-6.106 10.425a.5.5 0 0 1 .063.272l-.015.094l-.755 3.02l3.024-.752a.5.5 0 0 1 .187-.011l.092.021l.087.038A7 7 0 1 0 10 3m2.646 4.646a.5.5 0 1 1 .707.708l-4 4a.5.5 0 0 1-.707 0l-2-2a.5.5 0 1 1 .708-.708L9 11.293z");
}

</style>
