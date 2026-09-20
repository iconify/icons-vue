<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvm9cwbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvm9cwbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-ai-2-line" /></template>
