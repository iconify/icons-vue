<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxjc8704e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-24-filled" /></template>
<style>
.cxjc8704e {
  fill: currentColor;
  d: path("M5.25 3A3.25 3.25 0 0 0 2 6.25v8.5A3.25 3.25 0 0 0 5.25 18H6v2.75c0 1.03 1.176 1.618 2 1L13 18h5.75A3.25 3.25 0 0 0 22 14.75v-8.5A3.25 3.25 0 0 0 18.75 3z");
}

</style>
