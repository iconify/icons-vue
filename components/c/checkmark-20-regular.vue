<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rs_w9tb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-20-regular" /></template>
<style>
.rs_w9tb8y {
  fill: currentColor;
  d: path("M3.374 10.168a.5.5 0 0 0-.748.664l4 4.5a.5.5 0 0 0 .728.022l10.5-10.5a.5.5 0 0 0-.707-.708L7.02 14.271z");
}

</style>
