<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wwqx23bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-trending-16-filled" /></template>
<style>
.wwqx23bnd {
  fill: currentColor;
  d: path("M3.5 2.75a.75.75 0 0 0-1.5 0v8.5A2.75 2.75 0 0 0 4.75 14h8.5a.75.75 0 0 0 0-1.5h-8.5c-.69 0-1.25-.56-1.25-1.25zm6.25 2c0 .414.336.75.75.75h.94L9 7.94L7.53 6.47a.75.75 0 0 0-1.06 0l-1.5 1.5a.75.75 0 0 0 1.06 1.06L7 8.06l1.47 1.47a.75.75 0 0 0 1.06 0l2.97-2.97v1.017a.75.75 0 0 0 1.5 0V4.75a.75.75 0 0 0-.75-.75H10.5a.75.75 0 0 0-.75.75");
}

</style>
