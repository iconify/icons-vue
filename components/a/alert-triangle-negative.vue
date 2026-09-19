<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/shb7m1c7p.css';
import '../../css/s/smq0d-xen.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsAlertTriangleNegative0)" class="cuyn6tgcc"><path class="shb7m1c7p"/><path clip-rule="evenodd" class="smq0d-xen"/></g><defs><clipPath id="healthiconsAlertTriangleNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:alert-triangle-negative" /></template>
