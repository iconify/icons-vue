<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn262acok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vn262acok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:club-suit" /></template>
