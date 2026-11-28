<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvuuooufu.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u1xbpzeux.css';
import '../../css/k/kbxpyqdun.css';
import '../../css/g/gs05fwbhe.css';
import '../../css/z/ztl4i1bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvuuooufu secondary"/><g class="dt0cm9dhy primary"><path class="u1xbpzeux"/><path class="kbxpyqdun"/><path class="gs05fwbhe"/><path class="ztl4i1bdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-king-duo" /></template>
