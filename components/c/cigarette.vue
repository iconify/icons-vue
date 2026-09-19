<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frlfe4b7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="frlfe4b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cigarette" /></template>
