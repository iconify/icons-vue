<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmyrtdb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<rect class="mmyrtdb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-control-button-stop-button-television-buttons-movies-stop-tv-video-controls" /></template>
