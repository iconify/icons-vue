<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m_oqwybmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-down-double-20-filled" /></template>
<style>
.m_oqwybmn {
  fill: currentColor;
  d: path("M7.354 13.854L9 12.207a.5.5 0 1 0-.707-.707l-.793.793V6.5a.5.5 0 0 0-1 0v5.793l-.793-.793a.5.5 0 1 0-.707.707l1.646 1.647a.5.5 0 0 0 .708 0M18 10a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-4.646 3.854L15 12.207a.5.5 0 1 0-.707-.707l-.793.793V6.5a.5.5 0 0 0-1 0v5.793l-.793-.793a.5.5 0 1 0-.707.707l1.646 1.647a.5.5 0 0 0 .708 0");
}

</style>
