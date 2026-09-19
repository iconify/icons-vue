<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xi01rxbal.css';
import '../../css/c/ccnbmpbeo.css';
import '../../css/w/wggo06bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xi01rxbal"/><path class="ccnbmpbeo"/><path class="wggo06bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:figma-reset-instance" /></template>
