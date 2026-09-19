<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnv4d6brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pnv4d6brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:backhand-index-pointing-up" /></template>
