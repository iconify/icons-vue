<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/k/kvnvcfb9m.css';
import '../../css/x/xy97x4bhm.css';
import '../../css/v/v5afgebvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="kvnvcfb9m"/><path class="xy97x4bhm"/><path class="v5afgebvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cake-four" /></template>
