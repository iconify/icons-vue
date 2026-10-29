<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sj279cslk.css';
import '../../css/k/k4othtbmn.css';
import '../../css/t/t99xelbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sj279cslk"/><path class="k4othtbmn wm-a"/><path class="t99xelbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-open-duo" /></template>
