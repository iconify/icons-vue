<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x38bp_tbj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b00ennbgq.css';
import '../../css/e/e-3suj6zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x38bp_tbj"/><g class="dt0cm9dhy primary"><path class="b00ennbgq"/><path class="e-3suj6zv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-three-quarter-duo" /></template>
