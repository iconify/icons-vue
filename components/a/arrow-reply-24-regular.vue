<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujjbk3b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-24-regular" /></template>
<style>
.ujjbk3b6k {
  fill: currentColor;
  d: path("M9.28 6.28a.75.75 0 0 0-1.06-1.06l-5 5a.75.75 0 0 0 0 1.06l5 5a.75.75 0 0 0 1.06-1.06L5.56 11.5h7.69a6.25 6.25 0 0 1 6.25 6.25v.5a.75.75 0 0 0 1.5 0v-.5A7.75 7.75 0 0 0 13.25 10H5.56z");
}

</style>
