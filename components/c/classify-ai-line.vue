<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbby8qbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbby8qbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-ai-line" /></template>
