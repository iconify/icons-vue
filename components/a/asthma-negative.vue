<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pib7kkb6c.css';
import '../../css/a/ag30rjbba.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsAsthmaNegative0)" class="cuyn6tgcc"><path class="pib7kkb6c"/><path clip-rule="evenodd" class="ag30rjbba"/></g><defs><clipPath id="healthiconsAsthmaNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:asthma-negative" /></template>
