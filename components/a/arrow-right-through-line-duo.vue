<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rm-idea5h.css';
import '../../css/q/qu307c6jr.css';
import '../../css/p/p21j3ibnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="rm-idea5h"/><path class="qu307c6jr"/><path class="p21j3ibnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-right-through-line-duo" /></template>
