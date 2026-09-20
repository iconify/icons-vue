<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vbadqictn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-right-16-filled" /></template>
<style>
.vbadqictn {
  fill: currentColor;
  d: path("M7 13.25c0 .414.335.75.75.75h5.5a.75.75 0 0 0 .75-.75v-5.5a.75.75 0 0 0-1.5 0v3.69L3.28 2.22a.75.75 0 1 0-1.06 1.06l9.22 9.22H7.75a.75.75 0 0 0-.75.75");
}

</style>
