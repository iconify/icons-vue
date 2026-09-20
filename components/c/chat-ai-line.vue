<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6pj2c7fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6pj2c7fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-ai-line" /></template>
