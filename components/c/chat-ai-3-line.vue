<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slhog6bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slhog6bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-ai-3-line" /></template>
