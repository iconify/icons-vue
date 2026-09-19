<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqsyxlugg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vqsyxlugg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:camera-video-off-fill" /></template>
