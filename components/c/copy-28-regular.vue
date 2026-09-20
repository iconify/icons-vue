<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mebgwnkqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-28-regular" /></template>
<style>
.mebgwnkqo {
  fill: currentColor;
  d: path("M10 9.5H6.75a2.25 2.25 0 0 0-2.25 2.25v9.5a2.25 2.25 0 0 0 2.25 2.25h6.5a2.25 2.25 0 0 0 2.25-2.25V21H17v.25A3.75 3.75 0 0 1 13.25 25h-6.5A3.75 3.75 0 0 1 3 21.25v-9.5A3.75 3.75 0 0 1 6.75 8H10zM21.25 3A3.75 3.75 0 0 1 25 6.75v9.5A3.75 3.75 0 0 1 21.25 20h-6.5A3.75 3.75 0 0 1 11 16.25v-9.5A3.75 3.75 0 0 1 14.75 3zm-6.5 1.5a2.25 2.25 0 0 0-2.25 2.25v9.5a2.25 2.25 0 0 0 2.25 2.25h6.5a2.25 2.25 0 0 0 2.25-2.25v-9.5a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
