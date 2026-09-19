<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/wm4p_6bwr.css';
import '../../css/k/ktu665dou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wm4p_6bwr"/><path class="ktu665dou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:camera-foto-outline" /></template>
