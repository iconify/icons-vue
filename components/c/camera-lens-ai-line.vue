<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxwbhhyoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxwbhhyoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-lens-ai-line" /></template>
