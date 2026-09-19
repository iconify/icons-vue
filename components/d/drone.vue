<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/rq-hfbc3v.css';
import '../../css/q/qzbmf2tvd.css';
import '../../css/i/i-oj57g7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="rq-hfbc3v"/><path class="qzbmf2tvd"/><path class="i-oj57g7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:drone" /></template>
