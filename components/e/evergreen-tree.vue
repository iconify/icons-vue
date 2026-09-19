<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hysehgb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hysehgb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:evergreen-tree" /></template>
