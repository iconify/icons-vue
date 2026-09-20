<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oo15_y4yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-right-16-filled" /></template>
<style>
.oo15_y4yy {
  fill: currentColor;
  d: path("M8 15A7 7 0 1 0 8 1a7 7 0 0 0 0 14m3.462-6.809a.5.5 0 0 1-.106.16l-.003.003l-2.5 2.5a.5.5 0 0 1-.707-.708L9.793 8.5H5a.5.5 0 0 1 0-1h4.793L8.146 5.854a.5.5 0 1 1 .708-.708l2.5 2.5l.002.003a.5.5 0 0 1 .106.542");
}

</style>
