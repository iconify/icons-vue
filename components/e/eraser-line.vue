<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl98cu6fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl98cu6fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eraser-line" /></template>
