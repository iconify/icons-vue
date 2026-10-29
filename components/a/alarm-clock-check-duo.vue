<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n0z19zblo.css';
import '../../css/y/yemy-actk.css';
import '../../css/c/c91kb2byc.css';
import '../../css/l/lztux4j4y.css';
import '../../css/g/ghyktpbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n0z19zblo"/><path class="wm-a yemy-actk"/><path class="c91kb2byc wm-s"/><path class="lztux4j4y"/><path class="ghyktpbhu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-check-duo" /></template>
