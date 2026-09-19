<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m_jg-0icb.css';
import '../../css/a/aphxwuktr.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsHomeNegative0)" class="cuyn6tgcc"><path class="m_jg-0icb"/><path clip-rule="evenodd" class="aphxwuktr"/></g><defs><clipPath id="healthiconsHomeNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:home-negative" /></template>
