<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e9bm3i9jh.css';
import '../../css/y/yg3x3ublv.css';
import '../../css/y/y_g8ifbsl.css';
import '../../css/u/u_i2j5blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e9bm3i9jh"/><circle class="yg3x3ublv"/><circle class="y_g8ifbsl"/><circle class="u_i2j5blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:anchor-round" /></template>
