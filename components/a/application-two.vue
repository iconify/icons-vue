<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly6jl_bkj.css';
import '../../css/q/qgei9b-2x.css';
import '../../css/q/qd28qqumi.css';
import '../../css/n/nzo8xybpk.css';
import '../../css/w/wb2xu6o9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ly6jl_bkj"><circle class="qgei9b-2x"/><circle class="qd28qqumi"/><circle class="nzo8xybpk"/><circle class="wb2xu6o9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:application-two" /></template>
