<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amvs3v-lt.css';
import '../../css/k/k1w7nccir.css';
import '../../css/i/i6cvhyb1z.css';
import '../../css/k/k2sbuyjdj.css';
import '../../css/g/gkle75b_i.css';
import '../../css/z/z04drlb1l.css';
import '../../css/q/qg8n_wb1f.css';
import '../../css/l/l8_y2hs9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="amvs3v-lt"/><path class="k1w7nccir"/><path class="i6cvhyb1z"/><path class="k2sbuyjdj"/><path class="gkle75b_i"/><g class="z04drlb1l"><path class="qg8n_wb1f"/><path class="l8_y2hs9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:beverage-box" /></template>
