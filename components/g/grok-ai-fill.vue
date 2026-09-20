<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/funda6eji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="funda6eji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:grok-ai-fill" /></template>
