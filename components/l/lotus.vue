<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/d/dxeb_oimn.css';
import '../../css/l/ll17zo0eo.css';
import '../../css/o/o0rnf8isg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="dxeb_oimn"/><path class="ll17zo0eo"/><path class="o0rnf8isg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:lotus" /></template>
