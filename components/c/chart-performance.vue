<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydjtsubuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydjtsubuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-performance" /></template>
