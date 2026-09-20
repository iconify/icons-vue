<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4ur9abjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ur9abjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-1-ai-line" /></template>
