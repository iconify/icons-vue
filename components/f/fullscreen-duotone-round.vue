<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl-g2gbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl-g2gbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-duotone-round" /></template>
