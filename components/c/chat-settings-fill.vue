<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zagh264zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zagh264zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-settings-fill" /></template>
