<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sggorvbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-off-16-regular" /></template>
<style>
.sggorvbhl {
  fill: currentColor;
  d: path("M1.147 1.315a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.708L8.113 8.989q-.057.009-.115.01a1 1 0 0 1-1-1q.001-.058.01-.115L5.124 6a3.5 3.5 0 0 0 .4 4.474a.5.5 0 0 1-.707.707a4.5 4.5 0 0 1-.407-5.895L3.343 4.22a6 6 0 0 0 .414 8.022a.5.5 0 0 1-.707.708a7 7 0 0 1-.417-9.44L1.147 2.022a.5.5 0 0 1 0-.707M12.242 3.05a.5.5 0 0 1 .707 0a7 7 0 0 1 .88 8.827l-.725-.725a6 6 0 0 0-.862-7.395a.5.5 0 0 1 0-.707m-1.768 1.768a.5.5 0 0 1 .707 0a4.5 4.5 0 0 1 .823 5.235l-.754-.754a3.5 3.5 0 0 0-.776-3.774a.5.5 0 0 1 0-.707");
}

</style>
