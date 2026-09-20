<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/e/e55z5e0sb.css';
import '../../css/s/s57r1zbzd.css';
import '../../css/f/fhdna9knv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="e55z5e0sb"/><path class="s57r1zbzd"/><path class="fhdna9knv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:chart-column-grow" /></template>
