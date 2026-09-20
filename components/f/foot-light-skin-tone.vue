<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzd4-tbsl.css';
import '../../css/x/x3z1wibsp.css';
import '../../css/z/z04drlb1l.css';
import '../../css/s/swak8ubny.css';
import '../../css/z/zja7hrpwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tzd4-tbsl"/><path class="x3z1wibsp"/><g class="z04drlb1l"><path class="swak8ubny"/><path class="zja7hrpwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:foot-light-skin-tone" /></template>
