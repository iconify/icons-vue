<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf6uh2ajn.css';
import '../../css/r/rco1lvblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf6uh2ajn"/><path class="rco1lvblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chat-2-ai-line" /></template>
