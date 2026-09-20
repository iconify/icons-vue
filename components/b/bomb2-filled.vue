<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lxf8azbfy.css';
import '../../css/w/wa36r8bnm.css';
import '../../css/d/dmx_tobyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lxf8azbfy"/><path clip-rule="evenodd" class="wa36r8bnm"/><path class="dmx_tobyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bomb2-filled" /></template>
