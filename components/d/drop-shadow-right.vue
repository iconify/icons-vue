<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/g/gd9inehhp.css';
import '../../css/z/zzmzu9bzw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGODUmedRR"><g class="hv130ab-t"><path clip-rule="evenodd" class="gd9inehhp"/><path class="zzmzu9bzw"/></g></mask></defs><path mask="url(#SVGODUmedRR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:drop-shadow-right" /></template>
