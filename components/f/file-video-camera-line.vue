<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxtz_pbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxtz_pbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-video-camera-line" /></template>
