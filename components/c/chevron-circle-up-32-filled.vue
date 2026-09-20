<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="de76cbb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-up-32-filled" /></template>
<style>
.de76cbb1e {
  fill: currentColor;
  d: path("M16 30C8.268 30 2 23.732 2 16S8.268 2 16 2s14 6.268 14 14s-6.268 14-14 14M9.293 17.293a1 1 0 1 0 1.414 1.414L16 13.414l5.293 5.293a1 1 0 0 0 1.414-1.414l-5.878-5.879l-.033-.028l-.08-.073A1 1 0 0 0 16 11.02c-.26-.003-.484.097-.718.293c-.05.041-.06.05-.11.1v.002z");
}

</style>
