<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv819rkth.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rg07q9b9f.css';
import '../../css/g/guparg41d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv819rkth secondary"/><g class="dt0cm9dhy primary"><path class="rg07q9b9f"/><path class="guparg41d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:angle-duo" /></template>
