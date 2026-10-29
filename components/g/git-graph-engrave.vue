<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jisnqccwm.css';
import '../../css/c/crumyuhlq.css';
import '../../css/e/ezzstpbxg.css';
import '../../css/m/mrpjhzbvf.css';
import '../../css/e/e1kj5y_ub.css';
import '../../css/z/zn3w76bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jisnqccwm wm-k"/><path class="crumyuhlq wm-a"/><path class="ezzstpbxg wm-shadow"/><path class="mrpjhzbvf wm-k"/><path class="e1kj5y_ub wm-a"/><path class="wm-a zn3w76bgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-graph-engrave" /></template>
