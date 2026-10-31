<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/i/ibf1tmbnw.css';
import '../../css/a/at1_n_jvg.css';
import '../../css/n/n1y1i5mpe.css';
import '../../css/w/w7cmvhb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ibf1tmbnw wm-shadow"/><path class="at1_n_jvg wm-shadow"/><path class="n1y1i5mpe"/><path class="w7cmvhb_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:cloud-rain-wind" /></template>
