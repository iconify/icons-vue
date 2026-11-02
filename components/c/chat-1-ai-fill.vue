<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emmbwibof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emmbwibof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-1-ai-fill" /></template>
