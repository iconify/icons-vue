<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m03t3ybdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="m03t3ybdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-control-button-pause-1-button-television-buttons-movies-tv-pause-video-controls" /></template>
