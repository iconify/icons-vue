<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i63bjac3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i63bjac3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-ai-line" /></template>
