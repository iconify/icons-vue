<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/te6p9ctda.css';
import '../../css/i/ip1axky2i.css';
import '../../css/i/ibsglmb5m.css';
import '../../css/c/cxtiu753i.css';
import '../../css/u/u7l_q6bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="te6p9ctda wm-k"/><path class="ip1axky2i wm-shine"/><path class="ibsglmb5m wm-shine"/><path class="cxtiu753i wm-shine"/><path class="u7l_q6bhh wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:file-x" /></template>
