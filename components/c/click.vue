<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/nwbhzkbcg.css';
import '../../css/y/ycul966hb.css';
import '../../css/c/c9-gn0brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="nwbhzkbcg"/><path clip-rule="evenodd" class="ycul966hb"/><path class="c9-gn0brd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:click" /></template>
