<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ijpy3m14r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-eq-20-filled" /></template>
<style>
.ijpy3m14r {
  fill: currentColor;
  d: path("M10 2a.75.75 0 0 1 .75.75v14.5a.75.75 0 0 1-1.5 0V2.75A.75.75 0 0 1 10 2m3.75 3a.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-1.5 0v-8.5a.75.75 0 0 1 .75-.75M7 5.75a.75.75 0 0 0-1.5 0v8.5a.75.75 0 0 0 1.5 0zM17.25 8a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 .75-.75M3.5 8.75a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 1.5 0z");
}

</style>
