<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycaxgab8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycaxgab8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-audio-line" /></template>
