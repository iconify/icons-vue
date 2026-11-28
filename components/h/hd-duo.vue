<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co2u-_axd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k_280xbgm.css';
import '../../css/p/ps-_u7tyq.css';
import '../../css/h/h3_zgubvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co2u-_axd secondary"/><g class="dt0cm9dhy primary"><path class="k_280xbgm"/><path class="ps-_u7tyq"/><path class="h3_zgubvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hd-duo" /></template>
