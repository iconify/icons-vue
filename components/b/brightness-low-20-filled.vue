<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q38ip-wuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:brightness-low-20-filled" /></template>
<style>
.q38ip-wuy {
  fill: currentColor;
  d: path("M10 3a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1A.5.5 0 0 1 10 3m0 3a4 4 0 1 0 0 8a4 4 0 0 0 0-8m0 7V7a3 3 0 1 1 0 6m6.5-2.5a.5.5 0 0 0 0-1h-1a.5.5 0 0 0 0 1zM10 15a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-1 0v-1a.5.5 0 0 1 .5-.5m-5.5-4.5a.5.5 0 0 0 0-1h-1a.5.5 0 0 0 0 1zm.646-5.354a.5.5 0 0 1 .708 0l.5.5a.5.5 0 1 1-.708.708l-.5-.5a.5.5 0 0 1 0-.708m.708 9.708a.5.5 0 0 1-.708-.708l.5-.5a.5.5 0 0 1 .708.708zm9-9.708a.5.5 0 0 0-.708 0l-.5.5a.5.5 0 0 0 .708.708l.5-.5a.5.5 0 0 0 0-.708m-.708 9.708a.5.5 0 0 0 .708-.708l-.5-.5a.5.5 0 0 0-.708.708z");
}

</style>
