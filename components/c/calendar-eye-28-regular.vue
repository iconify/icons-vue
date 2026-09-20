<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="twtjyqaof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-eye-28-regular" /></template>
<style>
.twtjyqaof {
  fill: currentColor;
  d: path("M20.5 15c3.59 0 6.5 3.667 6.5 5.5S24.09 26 20.5 26S14 22.333 14 20.5s2.91-5.5 6.5-5.5m1.25-12A3.25 3.25 0 0 1 25 6.25v9.404a8.6 8.6 0 0 0-1.5-.936V9.503h-19V21.75c0 .966.784 1.75 1.75 1.75h7.953a9.3 9.3 0 0 0 1.381 1.5H6.25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3zM20.5 17a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7m0 1.5a2 2 0 1 1 0 4a2 2 0 0 1 0-4M6.25 4.5A1.75 1.75 0 0 0 4.5 6.25v1.753h19V6.25a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
