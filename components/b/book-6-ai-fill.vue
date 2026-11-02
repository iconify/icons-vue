<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hev68328m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hev68328m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-6-ai-fill" /></template>
