<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0u5-rbmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0u5-rbmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:bubbles" /></template>
