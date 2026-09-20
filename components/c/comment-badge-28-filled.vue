<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="tzydnb5vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-badge-28-filled" /></template>
<style>
.tzydnb5vl {
  fill: currentColor;
  d: path("M20.536 3A4 4 0 0 0 26 8.463v8.787A3.75 3.75 0 0 1 22.25 21h-5.941l-6.536 4.715C8.616 26.549 7 25.723 7 24.295V21H5.75A3.75 3.75 0 0 1 2 17.25V6.75A3.75 3.75 0 0 1 5.75 3zM24 2a3 3 0 1 1 0 6a3 3 0 0 1 0-6");
}

</style>
