<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/u/uc806cc_b.css';
import '../../css/r/rp0tc0bpg.css';
import '../../css/f/fmadhnbwi.css';
import '../../css/o/o0qcwtbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="uc806cc_b"/><path class="rp0tc0bpg"/><path class="fmadhnbwi"/><path class="o0qcwtbtl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:alarm-clock" /></template>
