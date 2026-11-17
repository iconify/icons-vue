<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7u7l2b_d.css';
import '../../css/e/eoj636-ni.css';
import '../../css/m/mxms0bb9j.css';
import '../../css/p/pj_elnr1m.css';
import '../../css/r/r_hv0ib9i.css';
import '../../css/h/hic2w3gpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="b7u7l2b_d"/><path class="eoj636-ni"/><path class="mxms0bb9j"/><circle class="pj_elnr1m"/><circle class="r_hv0ib9i"/><circle class="hic2w3gpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apiko" /></template>
