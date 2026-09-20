<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="y83pn1baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-histogram-28-regular" /></template>
<style>
.y83pn1baz {
  fill: currentColor;
  d: path("M15.75 3a2.75 2.75 0 0 1 2.75 2.75V8h3.75A2.75 2.75 0 0 1 25 10.75v13.5a.75.75 0 0 1-.75.75H3.75a.75.75 0 0 1-.75-.75v-9.5A2.75 2.75 0 0 1 5.75 12H9.5V5.75A2.75 2.75 0 0 1 12.25 3zm-10 10.5c-.69 0-1.25.56-1.25 1.25v8.75h5v-10zm6.5-9c-.69 0-1.25.56-1.25 1.25V23.5h6V5.75c0-.69-.56-1.25-1.25-1.25zm6.25 19h5V10.75c0-.69-.56-1.25-1.25-1.25H18.5z");
}

</style>
