<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi311wbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi311wbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:audio-waveform" /></template>
