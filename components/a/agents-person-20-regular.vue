<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bkgsk6bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-person-20-regular" /></template>
<style>
.bkgsk6bqm {
  fill: currentColor;
  d: path("M9.498 2a.5.5 0 0 1 0 1h-2.81a.75.75 0 0 0-.635.35L2.11 9.6a.75.75 0 0 0 0 .8l3.869 6.133a1 1 0 0 0 .845.467h.02a1 1 0 0 0 .967-.742l3.406-12.774A2 2 0 0 1 13.15 2h.02a2 2 0 0 1 1.692.934l3.868 6.132c.36.57.36 1.297 0 1.868l-1.395 2.212a2.5 2.5 0 0 0-.608-.136c.478-.53.77-1.23.772-2l.386-.61a.75.75 0 0 0 0-.8l-3.868-6.133A1 1 0 0 0 13.17 3h-.02a1 1 0 0 0-.966.742L8.778 16.516A2 2 0 0 1 6.846 18h-.02a2 2 0 0 1-1.692-.933l-3.868-6.133a1.75 1.75 0 0 1 0-1.868l3.941-6.25A1.75 1.75 0 0 1 6.687 2zM16.5 14a1.5 1.5 0 0 1 1.5 1.5c0 1.245-1 2.5-3.5 2.5S11 16.75 11 15.5a1.5 1.5 0 0 1 1.5-1.5zm-2-5a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
