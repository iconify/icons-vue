<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h9z3grv4e.css';
import '../../css/p/p2v6v82hv.css';
import '../../css/m/m47bcrbvx.css';
import '../../css/s/s6g5f5bwh.css';
import '../../css/k/kwpurbbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h9z3grv4e wm-k"/><path class="p2v6v82hv wm-k"/><path class="m47bcrbvx wm-k"/><path class="s6g5f5bwh wm-shine"/><path class="kwpurbbtu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:life-buoy" /></template>
