<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/srhbvgbaj.css';
import '../../css/t/tgf1jxbcb.css';
import '../../css/h/hu_nuxbxh.css';
import '../../css/a/a9t4ey_1q.css';
import '../../css/p/p0km8_bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="srhbvgbaj"/><path class="tgf1jxbcb"/><path class="hu_nuxbxh"/><circle class="a9t4ey_1q"/><path class="p0km8_bsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:inspection" /></template>
