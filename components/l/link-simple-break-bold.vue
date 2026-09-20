<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lqm6xzb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:link-simple-break-bold" /></template>
<style>
.lqm6xzb9n {
  fill: currentColor;
  d: path("m218.45 122.43l-30.08 30.06a12 12 0 0 1-17-17l30.08-30.07a36 36 0 0 0-50.93-50.92l-30.04 30.09a12 12 0 0 1-17-17l30.07-30.06a60 60 0 0 1 84.87 84.88Zm-82.93 49l-30.07 30.08a36 36 0 0 1-50.92-50.93l30.06-30.07a12 12 0 0 0-17-17l-30.04 30.07a60 60 0 0 0 84.88 84.87l30.06-30.07a12 12 0 0 0-17-17Z");
}

</style>
