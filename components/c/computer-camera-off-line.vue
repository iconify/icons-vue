<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkx4vubwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkx4vubwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-camera-off-line" /></template>
