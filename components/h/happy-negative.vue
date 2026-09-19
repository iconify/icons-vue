<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sm_f0rb5o.css';
import '../../css/q/qa6uieb3t.css';
import '../../css/n/ngfx-vbzr.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsHappyNegative0)" class="cuyn6tgcc"><path class="sm_f0rb5o"/><path clip-rule="evenodd" class="qa6uieb3t"/><path clip-rule="evenodd" class="ngfx-vbzr"/></g><defs><clipPath id="healthiconsHappyNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:happy-negative" /></template>
