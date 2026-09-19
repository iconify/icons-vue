<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al122vbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al122vbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:camera-video-light" /></template>
