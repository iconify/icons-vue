<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wndgu8_xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wndgu8_xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:audio-waveform" /></template>
