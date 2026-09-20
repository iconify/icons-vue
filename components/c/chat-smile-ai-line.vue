<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xacu3z89s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xacu3z89s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-ai-line" /></template>
