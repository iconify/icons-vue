<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w-i4zi3or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-add-20-regular" /></template>
<style>
.w-i4zi3or {
  fill: currentColor;
  d: path("M15.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.498 2a.5.5 0 1 1 0 1h-2.81a.75.75 0 0 0-.635.35L2.11 9.6a.75.75 0 0 0 0 .8l3.868 6.133c.183.29.503.467.846.467h.02a1 1 0 0 0 .967-.742l3.406-12.774A2 2 0 0 1 13.15 2h.02a2 2 0 0 1 1.692.934l3.868 6.132c.226.357.309.775.252 1.177a5.5 5.5 0 0 0-1.148-.724l-3.817-6.052A1 1 0 0 0 13.17 3h-.02a1 1 0 0 0-.966.742L8.778 16.516A2 2 0 0 1 6.846 18h-.02a2 2 0 0 1-1.692-.933l-3.868-6.133a1.75 1.75 0 0 1 0-1.868l3.941-6.25A1.75 1.75 0 0 1 6.687 2zM15.5 12a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H15v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 1 0 0-1H16v-1.5a.5.5 0 0 0-.5-.5");
}

</style>
