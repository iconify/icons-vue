<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-llkv2cb.css';
import '../../css/s/sll_zg-uo.css';
import '../../css/u/uo-caqnwu.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/h/hkem_-bvr.css';
import '../../css/f/f8ym9xb1c.css';
import '../../css/w/wmf-d-byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGhkI69czI" x1="16" x2="16" y1="0" y2="30" gradientUnits="userSpaceOnUse"><stop offset="0%" class="d-llkv2cb"/><stop offset="100%" class="sll_zg-uo"/></linearGradient><filter id="SVGEnb3ycdG" width="1.08" height="1.097" x="-.04" y="-.04" filterUnits="objectBoundingBox"><feOffset dy=".5" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation=".5"/><feComposite in="shadowBlurOuter1" in2="SourceAlpha" operator="out" result="shadowBlurOuter1"/><feColorMatrix in="shadowBlurOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.199473505 0"/></filter><circle id="SVGwsymTFGr" class="uo-caqnwu"/></defs><use filter="url(#SVGEnb3ycdG)" href="#SVGwsymTFGr" class="d2kvgvbvc"/><use href="#SVGwsymTFGr" class="hkem_-bvr"/><use fill="url(#SVGhkI69czI)" href="#SVGwsymTFGr" class="d2kvgvbvc"/><circle class="f8ym9xb1c"/><path class="wmf-d-byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:algorand" /></template>
