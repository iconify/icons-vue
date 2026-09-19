<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qm-ztbkwv.css';
import '../../css/r/roeu562tf.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsDNegative0)" class="cuyn6tgcc"><path class="qm-ztbkwv"/><path clip-rule="evenodd" class="roeu562tf"/></g><defs><clipPath id="healthiconsDNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:d-negative" /></template>
