<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inw1nccqb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a7mgnpb7z.css';
import '../../css/n/nk3w2sk1d.css';
import '../../css/g/g8hv7acos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inw1nccqb secondary"/><g class="dt0cm9dhy primary"><path class="a7mgnpb7z"/><path class="nk3w2sk1d"/><path class="g8hv7acos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:coins-duo" /></template>
