<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx7u0vbij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx7u0vbij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-2-ai-fill" /></template>
