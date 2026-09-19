<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/f_gjtjbcv.css';
import '../../css/x/x-ekx3b1l.css';
import '../../css/t/twe32ssqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="f_gjtjbcv"/><path class="x-ekx3b1l"/><path class="twe32ssqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:creative" /></template>
