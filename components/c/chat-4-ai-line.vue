<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-vq1vbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-vq1vbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-4-ai-line" /></template>
