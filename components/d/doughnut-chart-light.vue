<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/u/u8xc5ebwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="m4l-9ybuj"/><circle class="aqhok2bbj"/><path class="u8xc5ebwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:doughnut-chart-light" /></template>
