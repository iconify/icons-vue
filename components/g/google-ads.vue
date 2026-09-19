<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/cblyjfbfa.css';
import '../../css/t/tzb2l-bbx.css';
import '../../css/l/lsvuykfaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="cblyjfbfa"/><path class="tzb2l-bbx"/><circle transform="rotate(25 12.083 36.688)" class="lsvuykfaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:google-ads" /></template>
