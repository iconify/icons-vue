<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm_pr0vcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm_pr0vcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eraser-ai-fill" /></template>
