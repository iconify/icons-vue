<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7vn3acim.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/voyx-49xj.css';
import '../../css/v/vsmubdx_a.css';
import '../../css/p/pmtkcackh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x7vn3acim"/><g class="dt0cm9dhy primary"><path class="voyx-49xj"/><path class="vsmubdx_a"/><path class="pmtkcackh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chess-knight-duo" /></template>
