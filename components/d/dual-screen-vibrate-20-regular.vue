<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="diu2q8b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-vibrate-20-regular" /></template>
<style>
.diu2q8b_d {
  fill: currentColor;
  d: path("M7 5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2zM6 7a1 1 0 0 1 1-1h2.5v8H7a1 1 0 0 1-1-1zm4.5 7V6H13a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1zm1-1.5a.5.5 0 0 1 .5-.5h.5a.5.5 0 0 1 0 1H12a.5.5 0 0 1-.5-.5m-4-.5a.5.5 0 0 0 0 1H8a.5.5 0 0 0 0-1zM1.877 6.515a.5.5 0 0 1 .606.364l.41 1.64a1.5 1.5 0 0 1-.113 1.035l-.611 1.222a.5.5 0 0 0 0 .448l.776 1.552a.5.5 0 1 1-.894.448l-.776-1.553a1.5 1.5 0 0 1 0-1.342l.61-1.222a.5.5 0 0 0 .038-.345l-.41-1.64a.5.5 0 0 1 .364-.607m16.606.364a.5.5 0 0 0-.97.242l.41 1.641a.5.5 0 0 1-.037.345l-.611 1.222a1.5 1.5 0 0 0 0 1.342l.776 1.553a.5.5 0 1 0 .894-.448l-.776-1.552a.5.5 0 0 1 0-.448l.61-1.222c.161-.32.201-.687.114-1.034z");
}

</style>
