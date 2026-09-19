<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzsphib5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vzsphib5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:crossed-swords" /></template>
