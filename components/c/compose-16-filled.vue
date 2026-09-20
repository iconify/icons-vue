<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tw3c-2a_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:compose-16-filled" /></template>
<style>
.tw3c-2a_p {
  fill: currentColor;
  d: path("M8.25 3a.75.75 0 0 1 0 1.5h-3.5c-.69 0-1.25.56-1.25 1.25v5.5c0 .69.56 1.25 1.25 1.25h5.5c.69 0 1.25-.56 1.25-1.25v-3.5a.75.75 0 0 1 1.5 0v3.5A2.75 2.75 0 0 1 10.25 14h-5.5A2.75 2.75 0 0 1 2 11.25v-5.5A2.75 2.75 0 0 1 4.75 3zm4.47-.78a.75.75 0 1 1 1.06 1.06L7.59 9.47L6 10l.53-1.59z");
}

</style>
