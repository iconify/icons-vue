<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iub7stbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iub7stbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:joystick" /></template>
