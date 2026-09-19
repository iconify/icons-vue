<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/djrh81b_g.css';
import '../../css/d/de1yf9b_m.css';
import '../../css/f/fw02rxb_s.css';
import '../../css/e/eedmhxbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="djrh81b_g"/><path clip-rule="evenodd" class="de1yf9b_m"/><path clip-rule="evenodd" class="fw02rxb_s"/><path clip-rule="evenodd" class="eedmhxbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cancerous-cell-nuclei-outline" /></template>
