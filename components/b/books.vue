<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veu3tfbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="veu3tfbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:books" /></template>
