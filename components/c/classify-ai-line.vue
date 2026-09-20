<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibkxrtjjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibkxrtjjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-ai-line" /></template>
