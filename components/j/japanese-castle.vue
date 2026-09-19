<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtz7pxbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xtz7pxbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:japanese-castle" /></template>
