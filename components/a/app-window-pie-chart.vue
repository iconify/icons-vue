<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/s3_lo5eyl.css';
import '../../css/o/ok-uoxbmh.css';
import '../../css/q/qonxbbjwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3_lo5eyl"/><path class="ok-uoxbmh"/><path class="qonxbbjwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:app-window-pie-chart" /></template>
