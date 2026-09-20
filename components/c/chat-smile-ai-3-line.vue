<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo1mgl7xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo1mgl7xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-ai-3-line" /></template>
