<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/ku_lujd1a.css';
import '../../css/f/fzvhi0bnt.css';
import '../../css/m/mav1hqb9l.css';
import '../../css/g/g5u9bib3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ku_lujd1a wm-k"/><path class="fzvhi0bnt wm-k"/><path class="mav1hqb9l wm-k"/><path class="g5u9bib3y wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:drag-handle" /></template>
