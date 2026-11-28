<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4grobig.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vpst-w2dv.css';
import '../../css/o/obphd_b_m.css';
import '../../css/i/ixlpo7bwo.css';
import '../../css/h/hbscqzbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4grobig secondary"/><g class="dt0cm9dhy primary"><path class="vpst-w2dv"/><path class="obphd_b_m"/><path class="ixlpo7bwo"/><path class="hbscqzbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-sparkles-duo" /></template>
