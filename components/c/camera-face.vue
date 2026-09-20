<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfyhsib7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfyhsib7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:camera-face" /></template>
