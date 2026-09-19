<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xhdah4bbl.css';
import '../../css/d/dpljr7bjn.css';
import '../../css/u/u034iysry.css';
import '../../css/e/el5mddb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="xhdah4bbl"/><path class="dpljr7bjn"/><path class="u034iysry"/><path class="el5mddb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:left-bar" /></template>
