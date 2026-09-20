<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5evbibky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-upward-alt-outline" /></template>
<style>
.q5evbibky {
  fill: currentColor;
  d: path("M11 18V8.8l-3.6 3.6L6 11l6-6l6 6l-1.4 1.4L13 8.8V18z");
}

</style>
