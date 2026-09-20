<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7vsbhs2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:divider-short-24-filled" /></template>
<style>
.p7vsbhs2e {
  fill: currentColor;
  d: path("M11 5v14a1 1 0 1 0 2 0V5a1 1 0 1 0-2 0");
}

</style>
