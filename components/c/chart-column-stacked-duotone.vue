<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d10hjnbyz.css';
import '../../css/q/qoffap17o.css';
import '../../css/r/r726-2bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d10hjnbyz"/><path class="qoffap17o"/><path class="r726-2bju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-column-stacked-duotone" /></template>
