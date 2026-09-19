<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/meo0i6kkk.css';
import '../../css/x/xsg7zu72j.css';
import '../../css/h/hsytook5g.css';
import '../../css/v/vfc_tmbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="meo0i6kkk"/><path clip-rule="evenodd" class="xsg7zu72j"/><path class="hsytook5g"/><path clip-rule="evenodd" class="vfc_tmbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:icd-11-outline" /></template>
