<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/id8-p4bmo.css';
import '../../css/p/p-e4iwb_m.css';
import '../../css/a/aavn8cvga.css';
import '../../css/d/d_k9hzb-w.css';
import '../../css/k/kigmoib5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="id8-p4bmo"/><path class="p-e4iwb_m wm-k"/><path class="aavn8cvga wm-a"/><path class="d_k9hzb-w wm-k"/><path class="kigmoib5x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gauge-sketch" /></template>
