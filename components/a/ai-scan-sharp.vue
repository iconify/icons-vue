<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c38-qxbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c38-qxbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:ai-scan-sharp" /></template>
