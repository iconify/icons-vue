<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fhuo6fxyk.css';
import '../../css/i/ivj0dyb1p.css';
import '../../css/c/cjivcabhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fhuo6fxyk"/><path class="ivj0dyb1p wm-a"/><path class="cjivcabhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cursor-duo" /></template>
