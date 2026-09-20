<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub30ixkmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub30ixkmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-4-ai-fill" /></template>
