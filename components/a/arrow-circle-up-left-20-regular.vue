<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsmpw10oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-left-20-regular" /></template>
<style>
.nsmpw10oj {
  fill: currentColor;
  d: path("M7.149 7.144A.5.5 0 0 1 7.5 7h5a.5.5 0 0 1 0 1H8.707l4.147 4.146a.5.5 0 0 1-.708.708L8 8.707V12.5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .144-.351zM10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-7 8a7 7 0 1 1 14 0a7 7 0 0 1-14 0");
}

</style>
