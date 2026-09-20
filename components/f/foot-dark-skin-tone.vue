<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj_n4-bzu.css';
import '../../css/q/qq4sgukxb.css';
import '../../css/z/z04drlb1l.css';
import '../../css/s/swak8ubny.css';
import '../../css/z/zja7hrpwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jj_n4-bzu"/><path class="qq4sgukxb"/><g class="z04drlb1l"><path class="swak8ubny"/><path class="zja7hrpwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:foot-dark-skin-tone" /></template>
