<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eimycabdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eimycabdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-4-ai-fill" /></template>
