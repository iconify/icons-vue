<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s_u7qeb7d.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsDomesticWorkerAltNegative0)"><path clip-rule="evenodd" class="s_u7qeb7d"/></g><defs><clipPath id="healthiconsDomesticWorkerAltNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:domestic-worker-alt-negative" /></template>
