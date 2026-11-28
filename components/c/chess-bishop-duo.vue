<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi_5gbxpy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i01j-sbop.css';
import '../../css/k/kbxpyqdun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zi_5gbxpy"/><g class="dt0cm9dhy primary"><path class="i01j-sbop"/><path class="kbxpyqdun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-bishop-duo" /></template>
