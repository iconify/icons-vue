<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cz6nrxb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-csv-20-filled" /></template>
<style>
.cz6nrxb9k {
  fill: currentColor;
  d: path("M3 12a2 2 0 0 1 2 2a.5.5 0 0 1-1 0a1 1 0 1 0-2 0v2a1 1 0 1 0 2 0a.5.5 0 0 1 1 0a2 2 0 1 1-4 0v-2a2 2 0 0 1 2-2m4.5 0A1.5 1.5 0 0 1 9 13.5a.5.5 0 0 1-.99.1l-.02-.2a.5.5 0 0 0-.99.1v.382a.5.5 0 0 0 .276.447l.895.447A1.5 1.5 0 0 1 9 16.118v.382a1.5 1.5 0 0 1-3 0a.5.5 0 0 1 .99-.1l.02.2a.5.5 0 0 0 .99-.1v-.382a.5.5 0 0 0-.276-.447l-.895-.447A1.5 1.5 0 0 1 6 13.882V13.5A1.5 1.5 0 0 1 7.5 12m5.528.335a.5.5 0 1 1 .944.33l-1.75 5a.5.5 0 0 1-.944 0l-1.75-5a.5.5 0 0 1 .944-.33l1.278 3.651zM10 6.5A1.5 1.5 0 0 0 11.5 8H16v8.5a1.5 1.5 0 0 1-1.5 1.5h-1.336l.002-.004l1.75-5a1.5 1.5 0 0 0-.778-1.853l-.142-.059l-.147-.043a1.5 1.5 0 0 0-1.706.821l-.059.143l-.334.954l-.334-.954l-.058-.143a1.5 1.5 0 0 0-1.706-.821l-.147.043a.94.94 0 0 0-.519.407a2.5 2.5 0 0 0-3.606.683A3 3 0 0 0 4 11.17V3.5A1.5 1.5 0 0 1 5.5 2H10zm5.75.5H11.5a.5.5 0 0 1-.5-.5V2.25z");
}

</style>
