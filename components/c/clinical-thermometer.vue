<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqnyyjbdj.css';
import '../../css/h/hjlyr7bax.css';
import '../../css/g/g_h88_bfm.css';
import '../../css/z/z543v39qv.css';
import '../../css/x/xygtswd1g.css';
import '../../css/q/qgjn3vb8f.css';
import '../../css/u/utwhasb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="yqnyyjbdj"/><path class="hjlyr7bax"/><rect transform="rotate(45 29.352 38.517)" class="g_h88_bfm"/><rect transform="rotate(45 32.15 35.116)" class="z543v39qv"/><rect transform="rotate(45 35.297 32.988)" class="xygtswd1g"/><rect transform="rotate(45 38.207 29.82)" class="qgjn3vb8f"/><rect transform="rotate(45 41.12 27.034)" class="utwhasb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:clinical-thermometer" /></template>
