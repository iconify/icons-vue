<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/am770-rkn.css';
import '../../css/s/s0wimxb5x.css';
import '../../css/j/jt6io-b3f.css';
import '../../css/i/i_bd-bc3e.css';
import '../../css/f/fveoaacpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="am770-rkn"/><path class="s0wimxb5x"/><circle class="jt6io-b3f"/><circle class="i_bd-bc3e"/><path class="fveoaacpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:angry" /></template>
