<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr7f2mopu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr7f2mopu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:audio-waveform-fill" /></template>
