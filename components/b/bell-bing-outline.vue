<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjzuz0oew.css';
import '../../css/d/dfd8n3ylg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjzuz0oew"/><path clip-rule="evenodd" class="dfd8n3ylg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bell-bing-outline" /></template>
