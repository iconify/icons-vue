<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtmoqe2id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-right-24-filled" /></template>
<style>
.gtmoqe2id {
  fill: currentColor;
  d: path("M8.706 16.234a.75.75 0 1 0 1.088 1.032l4.5-4.75a.75.75 0 0 0 0-1.032l-4.5-4.75a.75.75 0 0 0-1.088 1.032l3.3 3.484H2.75a.75.75 0 0 0 0 1.5h9.256zM22 12a3 3 0 1 0-6 0a3 3 0 0 0 6 0");
}

</style>
