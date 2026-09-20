<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgfo8_bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgfo8_bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-video-outline" /></template>
