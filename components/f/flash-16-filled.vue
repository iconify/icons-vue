<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dvypstb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-16-filled" /></template>
<style>
.dvypstb9u {
  fill: currentColor;
  d: path("M5.873 1a1 1 0 0 0-.959.714L3.031 8.036A.75.75 0 0 0 3.75 9h1.583l-1.28 4.389c-.384 1.316 1.324 2.2 2.178 1.128l6.607-8.3A.75.75 0 0 0 12.25 5h-2.03l.994-2.649A1 1 0 0 0 10.279 1z");
}

</style>
