<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvekuabrc.css';
import '../../css/r/rc7piybql.css';
import '../../css/v/vsbbm2bdu.css';
import '../../css/b/bqfct8bxm.css';
import '../../css/x/xsd125mfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><circle class="mvekuabrc"/><path class="rc7piybql"/><path class="vsbbm2bdu"/><path class="bqfct8bxm"/><path class="xsd125mfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bitcoin" /></template>
