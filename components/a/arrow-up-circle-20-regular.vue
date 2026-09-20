<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="otxzkxi8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-circle-20-regular" /></template>
<style>
.otxzkxi8w {
  fill: currentColor;
  d: path("m6.646 9.146l3-3a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L10.5 7.707V13.5a.5.5 0 0 1-1 0V7.707L7.354 9.854a.5.5 0 0 1-.708-.708M10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-7 8a7 7 0 1 1 14 0a7 7 0 0 1-14 0");
}

</style>
