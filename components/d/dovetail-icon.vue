<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":293};
const content = `<path class="z9u1asblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dovetail-icon" /></template>
<style>
.z9u1asblt {
  fill: var(--svg-color--230078, #230078);
  d: path("m256 182.857l-64 36.572v-73.143l-64-36.974l64-36.17l64 36.572zm-128.01-73.143l-64 36.572V73.143L0 36.57L64 0l63.99 36.571zm0 146.286l-64 36.571l.01-73.142l-64-36.572l63.99-36.571l64 36.571z");
}

</style>
