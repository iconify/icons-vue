<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lpb30_ozm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-square-12-filled" /></template>
<style>
.lpb30_ozm {
  fill: currentColor;
  d: path("M.998 3.248a2.25 2.25 0 0 1 2.25-2.25h2.504A2.25 2.25 0 0 1 8 3.161v2.677a2.25 2.25 0 0 1-1.5 2.036l.002-4.626a.75.75 0 0 0-.75-.75H3.248a.75.75 0 0 0-.75.75v2.504c0 .327.21.605.502.708v1.528A2.25 2.25 0 0 1 .998 5.752zM4 8.75A2.25 2.25 0 0 0 6.25 11h2.5A2.25 2.25 0 0 0 11 8.75v-2.5a2.25 2.25 0 0 0-2-2.236v1.529c.291.103.5.38.5.707v2.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1-.75-.75V4.128A2.25 2.25 0 0 0 4 6.25z");
}

</style>
