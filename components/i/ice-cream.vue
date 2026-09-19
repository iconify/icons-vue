<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brwlxwbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="brwlxwbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ice-cream" /></template>
