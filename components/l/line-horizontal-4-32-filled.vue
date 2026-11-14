<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rpifrsbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-32-filled" /></template>
<style>
.rpifrsbag {
  fill: currentColor;
  d: path("M28.75 25a1.25 1.25 0 1 1 0 2.5H3.25a1.25 1.25 0 1 1 0-2.5zm0-7a1.25 1.25 0 1 1 0 2.5H3.25a1.25 1.25 0 1 1 0-2.5zm0-7a1.25 1.25 0 1 1 0 2.5H3.25a1.25 1.25 0 1 1 0-2.5zm0-7a1.25 1.25 0 1 1 0 2.5H3.25a1.25 1.25 0 1 1 0-2.5z");
}

</style>
