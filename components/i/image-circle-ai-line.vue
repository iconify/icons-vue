<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt5x5sxcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt5x5sxcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-circle-ai-line" /></template>
