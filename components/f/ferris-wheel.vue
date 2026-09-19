<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccnad6bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ccnad6bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ferris-wheel" /></template>
