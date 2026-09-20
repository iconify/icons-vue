<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kz-w_gbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-16-regular" /></template>
<style>
.kz-w_gbta {
  fill: currentColor;
  d: path("M4 9V3h8.028l-1.935 2.71a.5.5 0 0 0 0 .58L12.028 9zm0 1h9a.5.5 0 0 0 .407-.79L11.114 6l2.293-3.21A.5.5 0 0 0 13 2H3.5a.5.5 0 0 0-.5.5v11a.5.5 0 0 0 1 0z");
}

</style>
