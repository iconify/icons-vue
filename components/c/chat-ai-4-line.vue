<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyw2gnuap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyw2gnuap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-ai-4-line" /></template>
