<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/c-elrgb8n.css';
import '../../css/n/nw9mp7bns.css';
import '../../css/t/t355hjgxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="c-elrgb8n"/><path class="nw9mp7bns"/><path class="t355hjgxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:full-selection" /></template>
