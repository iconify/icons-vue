<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/y91k6ybzh.css';
import '../../css/k/ktu665dou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y91k6ybzh"/><path class="ktu665dou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:camera-photo-outline" /></template>
