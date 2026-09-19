<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/w/wqc8scbug.css';
import '../../css/r/rrkgq8bse.css';
import '../../css/q/qowkpdb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="wqc8scbug"/><path class="rrkgq8bse"/><path class="qowkpdb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cake-four" /></template>
