<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czbb_xjwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="czbb_xjwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:chart-increasing" /></template>
