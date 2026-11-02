<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3k_qdceo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3k_qdceo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-decreasing-fill" /></template>
