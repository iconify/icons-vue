<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jdujuybgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-uv" /></template>
<style>
.jdujuybgb {
  fill: var(--svg-color--de5fe9, #de5fe9);
  d: path("m2 2.1l.11 25c.007 1.5 1.3 2.8 2.8 2.8l19-.079c1.5-.006 2.8-1.3 2.8-2.8h1.3v2.8h2.2l-.12-28l-13 .054l.054 11v7h-2.3l.054-6.9l-.054-11z");
}

</style>
