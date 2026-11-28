<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf4c73b8m.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mg0ugob5a.css';
import '../../css/g/gcq-pnbnm.css';
import '../../css/m/mebfxw_io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yf4c73b8m"/><g class="dt0cm9dhy primary"><path class="mg0ugob5a"/><path class="gcq-pnbnm"/><path class="mebfxw_io"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lamp-ceiling-duo" /></template>
