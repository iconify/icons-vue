<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u45dg3bwf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qeq7gbben.css';
import '../../css/j/jbsk87b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u45dg3bwf"/><g class="dt0cm9dhy primary"><path class="qeq7gbben"/><path class="jbsk87b5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:airplay-duo" /></template>
