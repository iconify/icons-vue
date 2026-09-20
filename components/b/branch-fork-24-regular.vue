<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymcvkccqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-fork-24-regular" /></template>
<style>
.ymcvkccqc {
  fill: currentColor;
  d: path("M11 5.5a3.5 3.5 0 0 1-3 3.465V11.5h6.25a2.25 2.25 0 0 0 2.25-2.25v-.395A3.502 3.502 0 0 1 17.5 2a3.5 3.5 0 0 1 .5 6.965v.285A3.75 3.75 0 0 1 14.25 13H8v2.035a3.5 3.5 0 1 1-1.5.11v-6.29A3.502 3.502 0 0 1 7.5 2A3.5 3.5 0 0 1 11 5.5m-3.5 2a2 2 0 1 0 0-4a2 2 0 0 0 0 4m10 0a2 2 0 1 0 0-4a2 2 0 0 0 0 4m-8 11a2 2 0 1 0-4 0a2 2 0 0 0 4 0");
}

</style>
