<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j037z-b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j037z-b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:lime" /></template>
