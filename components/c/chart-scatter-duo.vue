<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/klzcb2brj.css';
import '../../css/c/cw36_6mco.css';
import '../../css/l/lw3ir5-go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="klzcb2brj"/><path class="cw36_6mco wm-a"/><path class="lw3ir5-go"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-scatter-duo" /></template>
