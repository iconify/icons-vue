<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/w50s6tb_z.css';
import '../../css/j/j57v_ccdv.css';
import '../../css/x/xxkl7ut0j.css';
import '../../css/n/no2x-xgpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="w50s6tb_z"/><path class="j57v_ccdv"/><path class="xxkl7ut0j"/><path class="no2x-xgpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:log" /></template>
