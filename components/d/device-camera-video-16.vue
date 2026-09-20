<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hymmnccew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hymmnccew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-camera-video-16" /></template>
