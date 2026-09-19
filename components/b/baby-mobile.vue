<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/m-w6wgbel.css';
import '../../css/g/gxt_-fw7h.css';
import '../../css/l/l2x9dv0pz.css';
import '../../css/y/yij9-ib4c.css';
import '../../css/i/ib55f4h-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="m-w6wgbel"/><circle class="gxt_-fw7h"/><path class="l2x9dv0pz"/><path class="yij9-ib4c"/><path class="ib55f4h-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:baby-mobile" /></template>
