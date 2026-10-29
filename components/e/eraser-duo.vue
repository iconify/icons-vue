<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/ggy4urlmh.css';
import '../../css/f/feucwswsf.css';
import '../../css/i/ides4ac0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ggy4urlmh"/><path class="feucwswsf wm-a"/><path class="ides4ac0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:eraser-duo" /></template>
