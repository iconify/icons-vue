<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlouh3b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlouh3b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-ai-fill" /></template>
