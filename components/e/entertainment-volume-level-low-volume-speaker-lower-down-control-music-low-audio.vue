<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhm60xclg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qhm60xclg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:entertainment-volume-level-low-volume-speaker-lower-down-control-music-low-audio" /></template>
