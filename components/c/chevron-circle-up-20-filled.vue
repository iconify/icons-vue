<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ur6ot-bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-up-20-filled" /></template>
<style>
.ur6ot-bow {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 0 16 0a8 8 0 0 0-16 0m4.854 1.854a.5.5 0 0 1-.708-.708l3.5-3.5a.5.5 0 0 1 .708 0l3.5 3.5a.5.5 0 0 1-.708.708L10 8.707z");
}

</style>
