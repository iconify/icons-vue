<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1f0q4baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1f0q4baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cursor-ai-fill" /></template>
