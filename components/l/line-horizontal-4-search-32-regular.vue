<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a-qhe_7vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-search-32-regular" /></template>
<style>
.a-qhe_7vt {
  fill: currentColor;
  d: path("M29 25a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zM18.5 1a7.5 7.5 0 0 1 5.962 12.048l6.245 6.245a1 1 0 1 1-1.414 1.414l-6.245-6.245A7.5 7.5 0 1 1 18.5 1m7.965 19H3a1 1 0 1 1 0-2h21.465zM18.5 3a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11m-8.646 8c.204.706.492 1.377.853 2H3a1 1 0 1 1 0-2zm.853-7a9 9 0 0 0-.853 2H3a1 1 0 0 1 0-2z");
}

</style>
