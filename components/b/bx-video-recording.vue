<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xalk1bbvn.css';
import '../../css/r/r0ke4kbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xalk1bbvn"/><path class="r0ke4kbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-video-recording" /></template>
