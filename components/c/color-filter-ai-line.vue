<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi2p6dbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi2p6dbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:color-filter-ai-line" /></template>
