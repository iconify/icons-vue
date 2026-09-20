<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vgu_sy6od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-subtract-circle-20-filled" /></template>
<style>
.vgu_sy6od {
  fill: currentColor;
  d: path("M11.5 12a.5.5 0 1 0 0 1h3a.5.5 0 0 0 0-1zM10 18a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-1a6.97 6.97 0 0 1-4.584-1.71l9.875-9.874A7 7 0 0 1 10 17M5.5 7a.5.5 0 0 1 .5-.5h1v-1a.5.5 0 0 1 1 0v1h1a.5.5 0 1 1 0 1H8v1a.5.5 0 0 1-1 0v-1H6a.5.5 0 0 1-.5-.5");
}

</style>
