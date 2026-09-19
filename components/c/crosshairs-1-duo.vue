<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yz825ub8o.css';
import '../../css/k/kk86xcjkp.css';
import '../../css/z/zoqbvhk0e.css';
import '../../css/q/qc7b6fb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="yz825ub8o"/><path class="kk86xcjkp"/><path class="zoqbvhk0e"/><path class="qc7b6fb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crosshairs-1-duo" /></template>
