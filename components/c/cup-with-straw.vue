<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdap3vb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qdap3vb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cup-with-straw" /></template>
