<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kf4gucb4u.css';
import '../../css/x/xji954c1a.css';
import '../../css/q/qsvi_nbbq.css';
import '../../css/m/mo94rtywa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="kf4gucb4u"/><path class="xji954c1a"/><circle class="qsvi_nbbq"/><path class="mo94rtywa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:glasses-three" /></template>
