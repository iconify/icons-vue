<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yazgverul.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o-59dh1-x.css';
import '../../css/t/t-juw-ftj.css';
import '../../css/h/h5ats917a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yazgverul"/><g class="dt0cm9dhy primary"><path class="o-59dh1-x"/><path class="t-juw-ftj"/><path class="h5ats917a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:beer-bottle-duo" /></template>
