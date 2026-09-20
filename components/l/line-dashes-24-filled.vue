<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwbo197ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-dashes-24-filled" /></template>
<style>
.xwbo197ko {
  fill: currentColor;
  d: path("M21.707 2.297a1 1 0 0 1 0 1.414l-.5.5a1 1 0 1 1-1.414-1.414l.5-.5a1 1 0 0 1 1.414 0m-4.004 4a1 1 0 0 1 0 1.414l-.997.997a1 1 0 1 1-1.414-1.414l.997-.997a1 1 0 0 1 1.414 0m-4.496 4.496a1 1 0 0 1 0 1.414l-1 1a1 1 0 0 1-1.414-1.414l1-1a1 1 0 0 1 1.414 0M8.703 16.71a1 1 0 1 0-1.414-1.414l-.998.997a1 1 0 1 0 1.414 1.415zm-4.491 4.496a1 1 0 0 0-1.414-1.414l-.5.5a1 1 0 0 0 1.414 1.414z");
}

</style>
