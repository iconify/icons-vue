<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl3cvobbt.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l24zqccfl.css';
import '../../css/q/qiuzifbed.css';
import '../../css/q/q6vbnacif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl3cvobbt secondary"/><g class="dt0cm9dhy primary"><path class="l24zqccfl"/><path class="qiuzifbed"/><path class="q6vbnacif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:lamp-desk-duo" /></template>
