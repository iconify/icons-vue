<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fuy0zyboz.css';
import '../../css/d/dyzl-zbur.css';
import '../../css/d/d6zxgccaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthicons4x4Negative0)" class="cuyn6tgcc"><path class="fuy0zyboz"/><path clip-rule="evenodd" class="dyzl-zbur"/></g><defs><clipPath id="healthicons4x4Negative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:4x4-negative" /></template>
