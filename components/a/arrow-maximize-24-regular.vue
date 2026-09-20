<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3fiplb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-24-regular" /></template>
<style>
.r3fiplb-v {
  fill: currentColor;
  d: path("M19.25 4a.75.75 0 0 1 .75.75v7.5a.75.75 0 0 1-1.5 0V6.56L6.56 18.5h5.69a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1-.75-.75v-7.5a.75.75 0 0 1 1.5 0v5.69L17.44 5.5h-5.69a.75.75 0 0 1 0-1.5z");
}

</style>
