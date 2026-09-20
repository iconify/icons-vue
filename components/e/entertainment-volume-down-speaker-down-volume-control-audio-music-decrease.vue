<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxce8tbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oxce8tbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-volume-down-speaker-down-volume-control-audio-music-decrease" /></template>
