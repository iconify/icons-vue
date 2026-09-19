<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8j66se8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e8j66se8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:brick" /></template>
