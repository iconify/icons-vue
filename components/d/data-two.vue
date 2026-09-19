<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/q97o_r-5j.css';
import '../../css/q/qzxir3brr.css';
import '../../css/v/vf4h32bmh.css';
import '../../css/i/ib2bsphlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><ellipse class="q97o_r-5j"/><path class="qzxir3brr"/><path class="vf4h32bmh"/><path class="ib2bsphlp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:data-two" /></template>
