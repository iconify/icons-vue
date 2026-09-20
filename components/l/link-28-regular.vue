<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="yxntjjs_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-28-regular" /></template>
<style>
.yxntjjs_b {
  fill: currentColor;
  d: path("M11 8a.75.75 0 0 1 .102 1.493L11 9.5H8a4.5 4.5 0 0 0-.212 8.995L8 18.5h3a.75.75 0 0 1 .102 1.493L11 20H8a6 6 0 0 1-.225-11.996L8 8zm9 0a6 6 0 0 1 .225 11.996L20 20h-3a.75.75 0 0 1-.102-1.493L17 18.5h3a4.5 4.5 0 0 0 .212-8.995L20 9.5h-3a.75.75 0 0 1-.102-1.493L17 8zM8 13.25h12a.75.75 0 0 1 .102 1.493L20 14.75H8a.75.75 0 0 1-.102-1.493zh12z");
}

</style>
