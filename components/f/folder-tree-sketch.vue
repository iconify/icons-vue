<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l6j_xaccc.css';
import '../../css/m/mn1bpcbjl.css';
import '../../css/z/z3y7eccgc.css';
import '../../css/k/kcrlnd2mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l6j_xaccc"/><path class="mn1bpcbjl wm-a"/><path class="wm-k z3y7eccgc"/><path class="kcrlnd2mp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-tree-sketch" /></template>
