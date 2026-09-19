<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m1vuaccwo.css';
import '../../css/c/cw0l96b5a.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsDefaultNegative0)" class="cuyn6tgcc"><path class="m1vuaccwo"/><path clip-rule="evenodd" class="cw0l96b5a"/></g><defs><clipPath id="healthiconsDefaultNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:default-negative" /></template>
