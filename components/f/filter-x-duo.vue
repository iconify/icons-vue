<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a35zb6y6e.css';
import '../../css/f/f9b4d59gs.css';
import '../../css/s/s0uk8_bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a35zb6y6e"/><path class="f9b4d59gs wm-s"/><path class="s0uk8_bdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:filter-x-duo" /></template>
