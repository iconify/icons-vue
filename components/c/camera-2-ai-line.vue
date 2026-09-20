<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl5xgp-7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl5xgp-7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-2-ai-line" /></template>
