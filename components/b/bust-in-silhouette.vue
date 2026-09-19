<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euq42txjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="euq42txjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bust-in-silhouette" /></template>
