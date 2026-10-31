<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8p-h-95k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8p-h-95k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-fill-round" /></template>
