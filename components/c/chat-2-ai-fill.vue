<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctdfjcn_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctdfjcn_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-2-ai-fill" /></template>
