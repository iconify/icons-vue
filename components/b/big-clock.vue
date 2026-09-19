<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/d/dx6c4tn2r.css';
import '../../css/r/r3z32eb1y.css';
import '../../css/j/j1xjnqltu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="dx6c4tn2r"/><circle class="r3z32eb1y"/><path class="j1xjnqltu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:big-clock" /></template>
