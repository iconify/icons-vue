<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jr8o5xbwo.css';
import '../../css/m/mio0p5byd.css';
import '../../css/i/ib7c11bau.css';
import '../../css/l/lybwfjbmr.css';
import '../../css/e/e64a3tb2y.css';
import '../../css/v/vca3m3c0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jr8o5xbwo"/><path class="mio0p5byd"/><path class="ib7c11bau"/><path class="lybwfjbmr"/><path clip-rule="evenodd" class="e64a3tb2y"/><path class="vca3m3c0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:head-side-mask" /></template>
