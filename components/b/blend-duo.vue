<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qflobibxt.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l7nm2qbhd.css';
import '../../css/r/rjuka2byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qflobibxt secondary"/><g class="dt0cm9dhy primary"><path class="l7nm2qbhd"/><path class="rjuka2byu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:blend-duo" /></template>
