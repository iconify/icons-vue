<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc6t_n4ay.css';
import '../../css/c/cqrap-bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc6t_n4ay"/><path class="cqrap-bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-doughnut-chart" /></template>
