<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff8ok2bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff8ok2bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-6-ai-fill" /></template>
