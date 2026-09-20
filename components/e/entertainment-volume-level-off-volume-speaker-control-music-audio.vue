<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7yby9bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="m7yby9bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-volume-level-off-volume-speaker-control-music-audio" /></template>
