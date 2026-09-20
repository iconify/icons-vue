<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6iikjgcv.css';
import '../../css/m/ms3y28bqn.css';
import '../../css/f/fg8_y-bfr.css';
import '../../css/z/zak-2ac5i.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/f/fqy6ynffm.css';
import '../../css/h/h35bbl50d.css';
import '../../css/d/d3i1wo8gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="s6iikjgcv"/><path class="ms3y28bqn"/><path class="fg8_y-bfr"/><path class="zak-2ac5i"/><g class="ij2x_72vy"><path class="fqy6ynffm"/><path class="h35bbl50d"/><path class="d3i1wo8gg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:face-with-medical-mask" /></template>
