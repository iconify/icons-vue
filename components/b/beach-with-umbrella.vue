<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xilpkgb-k.css';
import '../../css/i/ian6bfbdt.css';
import '../../css/t/t-jez5b4a.css';
import '../../css/v/vs5vt__md.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/l/ljehdzx8g.css';
import '../../css/c/cnfbru-tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xilpkgb-k"/><path class="ian6bfbdt"/><path class="t-jez5b4a"/><path class="vs5vt__md"/><g class="ij2x_72vy"><path class="ljehdzx8g"/><path class="cnfbru-tz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:beach-with-umbrella" /></template>
