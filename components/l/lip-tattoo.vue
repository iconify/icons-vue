<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bksp7_bys.css';
import '../../css/l/lbasq6h_m.css';
import '../../css/n/nn4_--rny.css';
import '../../css/l/lcx7m-3ja.css';
import '../../css/e/e2vr8o77x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="bksp7_bys"/><path class="lbasq6h_m"/><path class="nn4_--rny"/><path class="lcx7m-3ja"/><path class="e2vr8o77x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:lip-tattoo" /></template>
