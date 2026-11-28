<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib0-bt49v.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t_kpvabmz.css';
import '../../css/o/o10isi8cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib0-bt49v secondary"/><g class="dt0cm9dhy primary"><path class="t_kpvabmz"/><path class="o10isi8cf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:colon-duo" /></template>
