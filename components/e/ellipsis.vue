<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds88-_b_m.css';
import '../../css/y/ydri2mr6x.css';
import '../../css/r/rj1y-5bkj.css';
import '../../css/u/uu14cb_qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ds88-_b_m"><rect class="ydri2mr6x"/><rect class="rj1y-5bkj"/><rect class="uu14cb_qr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:ellipsis" /></template>
