<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kf5psab2d.css';
import '../../css/a/a3mskbb5v.css';
import '../../css/e/ev9ek8bsc.css';
import '../../css/w/wp96mgvab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><ellipse class="kf5psab2d"/><circle class="a3mskbb5v"/><path class="ev9ek8bsc"/><path class="wp96mgvab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:golf-course" /></template>
