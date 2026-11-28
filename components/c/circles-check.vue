<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e04hhlbss.css';
import '../../css/d/dqfo01btt.css';
import '../../css/q/q_oe4kopd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e04hhlbss"/><path class="dqfo01btt"/><path class="q_oe4kopd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circles-check" /></template>
