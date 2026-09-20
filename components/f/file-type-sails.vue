<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dmbb0_y-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sails" /></template>
<style>
.dmbb0_y-c {
  fill: var(--svg-color--28a3b2, #28a3b2);
  d: path("M4.6 30S-6.108 12.967 15.925 2v28zm14.737 0V12.645S22.853 18.381 30 30z");
}

</style>
