<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfsl22bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfsl22bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:camera-video-solid" /></template>
