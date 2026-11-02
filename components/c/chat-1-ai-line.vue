<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_k4pac1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_k4pac1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-1-ai-line" /></template>
