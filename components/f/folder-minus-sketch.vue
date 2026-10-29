<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fx9m6uqcj.css';
import '../../css/x/xq50ggbfl.css';
import '../../css/h/hiqlpgbhr.css';
import '../../css/m/mjpgeqf0d.css';
import '../../css/t/tug4xk1-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fx9m6uqcj"/><path class="xq50ggbfl"/><path class="hiqlpgbhr wm-k"/><path class="mjpgeqf0d"/><path class="tug4xk1-f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-minus-sketch" /></template>
