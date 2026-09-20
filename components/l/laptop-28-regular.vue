<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="otkgve-oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-28-regular" /></template>
<style>
.otkgve-oh {
  fill: currentColor;
  d: path("M6.754 5a2.75 2.75 0 0 0-2.75 2.75v8.5A2.75 2.75 0 0 0 6.754 19h14.5a2.75 2.75 0 0 0 2.75-2.75v-8.5A2.75 2.75 0 0 0 21.254 5zm-1.25 2.75c0-.69.56-1.25 1.25-1.25h14.5c.69 0 1.25.56 1.25 1.25v8.5c0 .69-.56 1.25-1.25 1.25h-14.5c-.69 0-1.25-.56-1.25-1.25zM2.754 20.5a.75.75 0 0 0 0 1.5H25.25a.75.75 0 0 0 0-1.5z");
}

</style>
