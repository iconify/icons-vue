<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nshr6y52x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nshr6y52x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:deciduous-tree" /></template>
