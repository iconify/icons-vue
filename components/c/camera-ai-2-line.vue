<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zll1bu97z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zll1bu97z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:camera-ai-2-line" /></template>
