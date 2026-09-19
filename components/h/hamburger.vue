<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lwc-i7bqs.css';
import '../../css/y/ysooycc-h.css';
import '../../css/j/jytgr1bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path clip-rule="evenodd" class="lwc-i7bqs"/><path class="ysooycc-h"/><path class="jytgr1bls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hamburger" /></template>
