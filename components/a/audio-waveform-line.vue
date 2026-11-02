<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxai5t9tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxai5t9tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:audio-waveform-line" /></template>
