<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jw_32pbvj.css';
import '../../css/v/vh8cdubgk.css';
import '../../css/e/ewja4-1ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><rect class="jw_32pbvj"/><path clip-rule="evenodd" class="vh8cdubgk"/><path class="ewja4-1ua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:enter-print" /></template>
