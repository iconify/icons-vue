<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9sxgvk4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s9sxgvk4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:incoming-envelope" /></template>
