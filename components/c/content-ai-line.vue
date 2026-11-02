<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqnfptala.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqnfptala"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:content-ai-line" /></template>
