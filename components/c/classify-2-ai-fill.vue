<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo-li9bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo-li9bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-2-ai-fill" /></template>
