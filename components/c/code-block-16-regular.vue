<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t2rv0sbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-block-16-regular" /></template>
<style>
.t2rv0sbyv {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zM3 4.5A1.5 1.5 0 0 1 4.5 3h7A1.5 1.5 0 0 1 13 4.5v7a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 11.5zm6.854 1.146a.5.5 0 1 0-.708.708L10.793 8L9.146 9.646a.5.5 0 0 0 .708.708l2-2a.5.5 0 0 0 0-.708zm-3 .708a.5.5 0 0 0-.708-.707l-2 2a.5.5 0 0 0 0 .707l2 2a.5.5 0 0 0 .708-.708L5.207 8z");
}

</style>
