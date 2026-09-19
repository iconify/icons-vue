<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/q/qgryp0big.css';
import '../../css/e/eif875blk.css';
import '../../css/u/uuadrccgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="qgryp0big"/><path clip-rule="evenodd" class="eif875blk"/><path class="uuadrccgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:bookmark" /></template>
