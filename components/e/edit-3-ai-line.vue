<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nna122kyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nna122kyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-3-ai-line" /></template>
