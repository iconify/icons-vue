<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qyqg0sbfa.css';
import '../../css/h/h11vkrbik.css';
import '../../css/x/xu_q_sbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qyqg0sbfa wm-k"/><path class="h11vkrbik wm-k"/><path class="wm-k xu_q_sbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:audio-waveform" /></template>
