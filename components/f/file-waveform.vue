<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt9lf65_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yt9lf65_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-waveform" /></template>
