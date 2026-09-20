<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ro5nwctwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-person-20-regular" /></template>
<style>
.ro5nwctwo {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1-3.613 15.139l-.121-.064l-3.645.91a.5.5 0 0 1-.62-.441v-.082l.014-.083l.91-3.645l-.064-.119C2.288 12.485 2.028 11.257 2 10a8 8 0 0 1 8-8m0 1a7 7 0 0 0-6.106 10.425a.5.5 0 0 1 .063.272l-.015.094l-.755 3.02l3.024-.753a.5.5 0 0 1 .187-.01l.092.021l.087.038A7 7 0 1 0 10 3m2.5 7a1.5 1.5 0 0 1 1.5 1.5c0 1.116-.459 2.01-1.212 2.615c-.741.595-1.735.885-2.788.885s-2.047-.29-2.788-.885C6.459 13.511 6 12.616 6 11.5A1.5 1.5 0 0 1 7.5 10zM10 5a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
