<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xo2z99k5u.css';
import '../../css/q/qp8wrac1e.css';
import '../../css/o/ofgf3ebhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="xo2z99k5u"/><circle transform="matrix(-1 0 0 1 33.5 24.5)" class="qp8wrac1e"/><path class="ofgf3ebhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:glasses-one" /></template>
