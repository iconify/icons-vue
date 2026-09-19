<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/p-amvacrb.css';
import '../../css/d/d0ox-ub5d.css';
import '../../css/p/pjdrmmvmh.css';
import '../../css/o/o2cr2ybri.css';
import '../../css/x/xjdbyrbde.css';
import '../../css/g/ghxp5qymf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="p-amvacrb"/><path class="d0ox-ub5d"/><path class="pjdrmmvmh"/><path class="o2cr2ybri"/><path class="xjdbyrbde"/><path class="ghxp5qymf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:blackboard" /></template>
