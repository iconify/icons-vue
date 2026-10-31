<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4l8xj2ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4l8xj2ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-three-quarter-fill-round" /></template>
