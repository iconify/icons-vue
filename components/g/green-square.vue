<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csudj1byh.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z-ncrnddp.css';
import '../../css/h/hmt31wfuj.css';
import '../../css/w/wts0-hiex.css';
import '../../css/z/zb6st5bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="SVGxSVQ7Qun" width="28" height="29" x="2" y="2" maskUnits="userSpaceOnUse" style="mask-type:alpha"><rect transform="matrix(0 -1 -1 0 30 30.145)" class="csudj1byh"/></mask><g class="ft5dv1b6b"><rect transform="matrix(-1 0 0 1 30 2)" class="z-ncrnddp"/><g mask="url(#SVGxSVQ7Qun)" class="hmt31wfuj"><path class="wts0-hiex"/></g><path class="zb6st5bnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:green-square" /></template>
