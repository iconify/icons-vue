<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/tu7lv1bwo.css';
import '../../css/l/lwmxsqbjy.css';
import '../../css/h/hygxn_ioi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="tu7lv1bwo"/><path class="lwmxsqbjy"/><path class="hygxn_ioi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:history" /></template>
