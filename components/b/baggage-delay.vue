<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/t8lnxgces.css';
import '../../css/n/n6762lb_a.css';
import '../../css/k/kfdh64trl.css';
import '../../css/d/dc83f5wdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="t8lnxgces"/><path class="n6762lb_a"/><path class="kfdh64trl"/><path class="dc83f5wdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:baggage-delay" /></template>
