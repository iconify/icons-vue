<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dcs14gb4n.css';
import '../../css/i/idfvs04zd.css';
import '../../css/i/izsxrmtpy.css';
import '../../css/k/k5_ti6n7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dcs14gb4n wm-k"/><path class="idfvs04zd wm-a"/><path class="izsxrmtpy wm-k"/><path class="k5_ti6n7q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-from-line-sketch" /></template>
