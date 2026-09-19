<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/sgouetkcw.css';
import '../../css/f/fqgji9b2o.css';
import '../../css/p/plqe-22_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="sgouetkcw"/><path class="fqgji9b2o"/><path class="plqe-22_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:baby-sling" /></template>
