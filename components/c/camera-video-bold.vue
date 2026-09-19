<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7zky1b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7zky1b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:camera-video-bold" /></template>
