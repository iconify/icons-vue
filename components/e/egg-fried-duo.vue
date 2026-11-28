<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tij9s_4ga.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sxtt7ca6r.css';
import '../../css/m/mydyanbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tij9s_4ga"/><g class="dt0cm9dhy primary"><path class="sxtt7ca6r"/><path class="mydyanbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:egg-fried-duo" /></template>
