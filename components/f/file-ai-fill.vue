<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuez5acdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuez5acdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-ai-fill" /></template>
