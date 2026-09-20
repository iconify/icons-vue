<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="elfjbhipn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:clock-user-fill" /></template>
<style>
.elfjbhipn {
  fill: currentColor;
  d: path("M136 72v43.06l36.42-18.22a8 8 0 1 1 7.16 14.32l-48 24A8 8 0 0 1 120 128V72a8 8 0 0 1 16 0m-8 144a88 88 0 1 1 88-88a8 8 0 0 0 16 0a104 104 0 1 0-104 104a8 8 0 0 0 0-16m86.62-17.38a32 32 0 1 0-45.24 0A40 40 0 0 0 152.27 222a8 8 0 0 0 7.73 10h64a8 8 0 0 0 7.73-10.06a40 40 0 0 0-17.11-23.32");
}

</style>
