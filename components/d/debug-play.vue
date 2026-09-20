<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g65pj_bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g65pj_bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:debug-play" /></template>
