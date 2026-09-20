<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymsfoqbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymsfoqbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-ai-4-fill" /></template>
