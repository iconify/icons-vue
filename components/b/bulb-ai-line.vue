<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p71seyb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p71seyb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-ai-line" /></template>
