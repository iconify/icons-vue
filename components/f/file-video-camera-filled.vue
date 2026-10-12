<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc5mk5wwa.css';
import '../../css/c/csdxkcclh.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc5mk5wwa"/><path class="csdxkcclh"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-video-camera-filled" /></template>
