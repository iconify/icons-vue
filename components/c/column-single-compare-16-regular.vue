<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="in2z9w1zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-single-compare-16-regular" /></template>
<style>
.in2z9w1zm {
  fill: currentColor;
  d: path("M3 2.75C3 1.784 3.784 1 4.75 1h6.5c.966 0 1.75.784 1.75 1.75v10.5A1.75 1.75 0 0 1 11.25 15h-6.5A1.75 1.75 0 0 1 3 13.25zM4.75 2a.75.75 0 0 0-.75.75V5h8V2.75a.75.75 0 0 0-.75-.75zM4 9h8V6H4zm0 2v2.25c0 .414.336.75.75.75h6.5a.75.75 0 0 0 .75-.75V11z");
}

</style>
