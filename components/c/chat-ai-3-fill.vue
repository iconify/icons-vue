<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_cx370op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_cx370op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-ai-3-fill" /></template>
