<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4biehbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-24-regular" /></template>
<style>
.v4biehbdx {
  fill: currentColor;
  d: path("M21.784 2.22a.75.75 0 0 1 0 1.06L3.28 21.784a.75.75 0 1 1-1.06-1.06L20.723 2.22a.75.75 0 0 1 1.06 0");
}

</style>
