<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf413j1th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf413j1th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-2-ai-fill" /></template>
