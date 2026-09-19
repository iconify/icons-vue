<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h6ixtxbck.css';
import '../../css/j/jqr3nvo3o.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthicons8Negative0)" class="cuyn6tgcc"><path class="h6ixtxbck"/><path clip-rule="evenodd" class="jqr3nvo3o"/></g><defs><clipPath id="healthicons8Negative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:8-negative" /></template>
