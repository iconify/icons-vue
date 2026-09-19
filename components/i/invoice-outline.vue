<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/k/k84t0ebpb.css';
import '../../css/u/un_j6acnf.css';
import '../../css/p/padmk1hmn.css';
import '../../css/w/wni6cpb8g.css';
import '../../css/q/q65zcy66p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="k84t0ebpb"/><path class="un_j6acnf"/><circle class="padmk1hmn"/><circle class="wni6cpb8g"/><path class="q65zcy66p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:invoice-outline" /></template>
