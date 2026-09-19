<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlaoe4boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mlaoe4boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:device-camera-video" /></template>
