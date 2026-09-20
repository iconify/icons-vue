<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h006f4bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-32-filled" /></template>
<style>
.h006f4bfk {
  fill: currentColor;
  d: path("M12.817 2.319a4.5 4.5 0 0 1 6.363 0l10.499 10.499a4.5 4.5 0 0 1 0 6.364L19.18 29.68a4.5 4.5 0 0 1-6.363 0l-10.5-10.498a4.5 4.5 0 0 1 0-6.364z");
}

</style>
