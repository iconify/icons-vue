<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juc8pebst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-reply-all" /></template>
<style>
.juc8pebst {
  fill: currentColor;
  d: path("M7 8V5l-7 7l7 7v-3l-4-4zm6 1V5l-7 7l7 7v-4.1c5 0 8.5 1.6 11 5.1c-1-5-4-10-11-11");
}

</style>
