<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi3hjdhnc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pg4__ow1p.css';
import '../../css/l/lo5g5bc_w.css';
import '../../css/r/rqhxtipmw.css';
import '../../css/t/t7x83a-tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yi3hjdhnc"/><g class="dt0cm9dhy primary"><path class="pg4__ow1p"/><path class="lo5g5bc_w"/><path class="rqhxtipmw"/><path class="t7x83a-tg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:input-search-duo" /></template>
