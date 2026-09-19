<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u_wpzfweg.css';
import '../../css/b/b-7hyhlyn.css';
import '../../css/u/uym-bnbal.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsBreastPumpNegative0)" class="cuyn6tgcc"><path class="u_wpzfweg"/><path clip-rule="evenodd" class="b-7hyhlyn"/><path clip-rule="evenodd" class="uym-bnbal"/></g><defs><clipPath id="healthiconsBreastPumpNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:breast-pump-negative" /></template>
