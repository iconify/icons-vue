<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kurhn23aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kurhn23aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-control-button-next-button-television-buttons-movies-skip-next-video-controls" /></template>
