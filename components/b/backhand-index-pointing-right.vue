<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yft98tjya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(32 0) scale(-1 1)"><path class="yft98tjya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:backhand-index-pointing-right" /></template>
