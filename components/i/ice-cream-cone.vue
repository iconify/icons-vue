<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i5f0lcbnp.css';
import '../../css/p/pt9ctxglj.css';
import '../../css/r/r4bva5bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i5f0lcbnp"/><path class="pt9ctxglj"/><path class="r4bva5bde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ice-cream-cone" /></template>
