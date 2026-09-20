<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jbiowtv7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-highlight-20-regular" /></template>
<style>
.jbiowtv7b {
  fill: currentColor;
  d: path("M9.715 3.006a7 7 0 0 1 1.729.143l2.204 2.204a.5.5 0 0 0 .707-.707l-.47-.47a7 7 0 1 1-9.717 9.697l.48.48a.5.5 0 1 0 .707-.707l-2.207-2.207a7 7 0 0 1-.142-1.728l1.892 1.892a.5.5 0 1 0 .707-.707L3.17 8.461q.14-.623.386-1.2l2.342 2.342a.5.5 0 1 0 .707-.707L4.038 6.329q.3-.485.672-.914l2.438 2.438a.5.5 0 1 0 .707-.707L5.417 4.708q.43-.372.915-.671l2.566 2.566a.5.5 0 1 0 .707-.707L7.264 3.555a7 7 0 0 1 1.2-.386l2.434 2.434a.5.5 0 0 0 .707-.707zM10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

</style>
