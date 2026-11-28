<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1vwxvzta.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kaowuknjg.css';
import '../../css/t/tw3edbbnp.css';
import '../../css/x/xd4r41bmd.css';
import '../../css/z/zhhiysb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1vwxvzta secondary"/><g class="dt0cm9dhy primary"><path class="kaowuknjg"/><path class="tw3edbbnp"/><path class="xd4r41bmd"/><path class="zhhiysb_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layout-dashboard-duo" /></template>
