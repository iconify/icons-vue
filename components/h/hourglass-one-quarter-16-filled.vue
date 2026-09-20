<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x3a8tbb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hourglass-one-quarter-16-filled" /></template>
<style>
.x3a8tbb5s {
  fill: currentColor;
  d: path("m6.113 11l-.095.08c-.296.257-.518.496-.683.806c-.13.247-.256.595-.31 1.114h5.946c-.054-.52-.179-.868-.31-1.114c-.164-.31-.386-.55-.681-.806L9.885 11z");
}

</style>
