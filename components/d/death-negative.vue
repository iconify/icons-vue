<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/arsctllsr.css';
import '../../css/s/syragybxy.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsDeathNegative0)" clip-rule="evenodd" class="n1lsf0bnc"><path class="arsctllsr"/><path class="syragybxy"/></g><defs><clipPath id="healthiconsDeathNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:death-negative" /></template>
