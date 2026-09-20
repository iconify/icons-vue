<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciz_d-bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ciz_d-bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-control-button-play-button-television-buttons-movies-play-tv-video-controls" /></template>
