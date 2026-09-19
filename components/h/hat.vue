<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/o3y-mwb9w.css';
import '../../css/z/zdq5ixbzs.css';
import '../../css/f/fi8jscb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="o3y-mwb9w"/><rect class="zdq5ixbzs"/><path class="fi8jscb1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hat" /></template>
