<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjw6t9bnm.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ajw6i38we.css';
import '../../css/h/h22d54nez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjw6t9bnm secondary"/><g class="dt0cm9dhy primary"><path class="ajw6i38we"/><path class="h22d54nez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dumpling-duo" /></template>
