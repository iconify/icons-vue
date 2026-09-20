<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4jbx15ww.css';
import '../../css/y/yj5_e8b5l.css';
import '../../css/t/t4zjezbtg.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/bfuou51dl.css';
import '../../css/s/slcpbtblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="v4jbx15ww"/><path class="yj5_e8b5l"/><path class="t4zjezbtg"/><g class="ij2x_72vy"><path class="bfuou51dl"/><path class="slcpbtblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:burrito" /></template>
