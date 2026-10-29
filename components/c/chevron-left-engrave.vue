<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mc09_q5oi.css';
import '../../css/j/j1q041bll.css';
import '../../css/f/fy7v02hzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mc09_q5oi"/><path class="j1q041bll wm-shadow"/><path class="fy7v02hzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-left-engrave" /></template>
