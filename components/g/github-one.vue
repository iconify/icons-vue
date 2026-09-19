<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/d/dvl8vktim.css';
import '../../css/j/j14g4-btm.css';
import '../../css/c/cmn4_l2kg.css';
import '../../css/q/qx21y284q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="dvl8vktim"/><path class="j14g4-btm"/><path class="cmn4_l2kg"/><path class="qx21y284q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:github-one" /></template>
