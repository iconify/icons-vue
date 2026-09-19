<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/o/o477sp5ja.css';
import '../../css/y/y0r_bqb0y.css';
import '../../css/p/p2pks0acd.css';
import '../../css/d/ddjdzib0d.css';
import '../../css/b/bp-k_tjsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="o477sp5ja"/><rect class="y0r_bqb0y"/><path class="p2pks0acd"/><path class="ddjdzib0d"/><path class="bp-k_tjsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hotel" /></template>
