<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/ni50ofboa.css';
import '../../css/l/luxlqfrxi.css';
import '../../css/v/v56dgzb1x.css';
import '../../css/e/e1lspva1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="ni50ofboa"/><path class="luxlqfrxi"/><path class="v56dgzb1x"/><path class="e1lspva1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:arrow-spin" /></template>
