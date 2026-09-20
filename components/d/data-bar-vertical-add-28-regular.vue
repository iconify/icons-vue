<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f1xqb8bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-add-28-regular" /></template>
<style>
.f1xqb8bjh {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M6 13a3 3 0 0 1 3 3v6a3 3 0 1 1-6 0v-6a3 3 0 0 1 3-3m8-5a3 3 0 0 1 3 3v2.866a7.5 7.5 0 0 0-1.5 1.044V11a1.5 1.5 0 0 0-3 0v11c0 .69.466 1.27 1.1 1.444c.232.542.526 1.051.873 1.519A3 3 0 0 1 11 22V11a3 3 0 0 1 3-3m6.5 8a.5.5 0 0 0-.5.5V20h-3.5a.5.5 0 0 0 0 1H20v3.5a.5.5 0 0 0 1 0V21h3.5a.5.5 0 0 0 0-1H21v-3.5a.5.5 0 0 0-.5-.5M6 14.5A1.5 1.5 0 0 0 4.5 16v6a1.5 1.5 0 0 0 3 0v-6A1.5 1.5 0 0 0 6 14.5M22 3a3 3 0 0 1 3 3v8.5a7.5 7.5 0 0 0-1.5-.874V6a1.5 1.5 0 0 0-3 0v7q-.772 0-1.5.15V6a3 3 0 0 1 3-3");
}

</style>
