<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp6grhbuz.css';
import '../../css/n/nwfiqubag.css';
import '../../css/w/wfpty7bmi.css';
import '../../css/x/xfy7c2bhu.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/n/nait7dcvs.css';
import '../../css/p/pex--j-eb.css';
import '../../css/d/deha53ifs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kp6grhbuz"/><path class="nwfiqubag"/><path class="wfpty7bmi"/><circle class="xfy7c2bhu"/><g class="ij2x_72vy"><path class="nait7dcvs"/><circle class="pex--j-eb"/><path class="deha53ifs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:key" /></template>
