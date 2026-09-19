<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xf9n0sgyw.css';
import '../../css/i/ibwpnye2s.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsHearingAidNegative0)" class="cuyn6tgcc"><path class="xf9n0sgyw"/><path clip-rule="evenodd" class="ibwpnye2s"/></g><defs><clipPath id="healthiconsHearingAidNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hearing-aid-negative" /></template>
