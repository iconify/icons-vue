<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s2gz3nbuh.css';
import '../../css/h/h-upcp83y.css';
import '../../css/t/tf9_0-uqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s2gz3nbuh"/><path class="h-upcp83y wm-a"/><path class="tf9_0-uqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hexagon-duo" /></template>
