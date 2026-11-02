<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zicn2_zap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zicn2_zap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-ai-line" /></template>
