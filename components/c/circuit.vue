<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw2zz0bco.css';
import '../../css/q/qwcw2dols.css';
import '../../css/e/ef8dd5fmv.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/j/jgtei1-7f.css';
import '../../css/o/o63jcwmgg.css';
import '../../css/s/s8dlyyvqf.css';
import '../../css/z/z39z3ib6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tw2zz0bco"/><path class="qwcw2dols"/><circle class="ef8dd5fmv"/><g class="ij2x_72vy"><path class="jgtei1-7f"/><path class="o63jcwmgg"/><circle class="s8dlyyvqf"/><path class="z39z3ib6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:circuit" /></template>
