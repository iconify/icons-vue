<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dq65a4e6h.css';
import '../../css/v/v40rf1bhl.css';
import '../../css/v/vbyp6jb4e.css';
import '../../css/l/l4y0xgwkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="dq65a4e6h"/><path class="v40rf1bhl"/><circle class="vbyp6jb4e"/><circle class="l4y0xgwkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:camera-two" /></template>
