<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag9jxsbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag9jxsbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:audio-waveform-sharp" /></template>
