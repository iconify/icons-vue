<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/n/ncw4z3bwh.css';
import '../../css/w/wps4e9ynm.css';
import '../../css/f/fz7419b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="ncw4z3bwh"/><path class="wps4e9ynm"/><path class="fz7419b1g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ic-1x1" /></template>
