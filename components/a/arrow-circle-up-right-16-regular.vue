<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vb5s5lpku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-right-16-regular" /></template>
<style>
.vb5s5lpku {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-7a7 7 0 1 0 0 14A7 7 0 0 0 8 1m3 4.5a.5.5 0 0 0-.5-.5H6a.5.5 0 0 0 0 1h3.293L5.646 9.646a.5.5 0 0 0 .708.708L10 6.707V10a.5.5 0 0 0 1 0z");
}

</style>
