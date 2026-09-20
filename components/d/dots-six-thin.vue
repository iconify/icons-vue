<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m9ssonb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dots-six-thin" /></template>
<style>
.m9ssonb7g {
  fill: currentColor;
  d: path("M68 92a8 8 0 1 1-8-8a8 8 0 0 1 8 8m60-8a8 8 0 1 0 8 8a8 8 0 0 0-8-8m68 16a8 8 0 1 0-8-8a8 8 0 0 0 8 8M60 156a8 8 0 1 0 8 8a8 8 0 0 0-8-8m68 0a8 8 0 1 0 8 8a8 8 0 0 0-8-8m68 0a8 8 0 1 0 8 8a8 8 0 0 0-8-8");
}

</style>
