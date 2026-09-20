<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/q/q1n9h3uve.css';
import '../../css/d/d7wp7yb4y.css';
import '../../css/s/smgbl8cgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="q1n9h3uve"/><path class="d7wp7yb4y"/><path class="smgbl8cgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:chart-column-low" /></template>
