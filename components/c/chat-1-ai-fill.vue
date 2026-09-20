<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-ch-u9hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-ch-u9hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-1-ai-fill" /></template>
