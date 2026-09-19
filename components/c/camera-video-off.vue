<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohbmzqx2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohbmzqx2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:camera-video-off" /></template>
