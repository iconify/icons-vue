<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jod2pk_tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-28-filled" /></template>
<style>
.jod2pk_tj {
  fill: currentColor;
  d: path("M10.707 5.293a1 1 0 0 1 0 1.414L6.414 11H15c5.523 0 10 4.477 10 10a1 1 0 1 1-2 0a8 8 0 0 0-8-8H6.414l4.293 4.293a1 1 0 0 1-1.414 1.414l-6-6a1 1 0 0 1 0-1.414l6-6a1 1 0 0 1 1.414 0");
}

</style>
