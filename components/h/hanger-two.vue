<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hfbsm1a_v.css';
import '../../css/v/ve3fiub2m.css';
import '../../css/w/w72sghb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hfbsm1a_v"/><path class="ve3fiub2m"/><path class="w72sghb3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hanger-two" /></template>
