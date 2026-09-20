<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pdsagcb-l.css';
import '../../css/x/xvqlmwgpz.css';
import '../../css/z/zmwvwabol.css';
import '../../css/l/luruawbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pdsagcb-l"/><path clip-rule="evenodd" class="xvqlmwgpz"/><path clip-rule="evenodd" class="zmwvwabol"/><path class="luruawbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:address-book" /></template>
