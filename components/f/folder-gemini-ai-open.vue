<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l32lerbfx.css';
import '../../css/l/l6_t7qyjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l32lerbfx"/><path class="l6_t7qyjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gemini-ai-open" /></template>
