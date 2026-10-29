<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/edbrcnc5p.css';
import '../../css/s/sky80ibxo.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/m/mj_mud4nl.css';
import '../../css/k/kjmig_qpk.css';
import '../../css/h/hnamav36t.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="edbrcnc5p wm-k"/><path class="sky80ibxo wm-a"/><path class="ol-kpp5cg wm-s"/><path class="mj_mud4nl wm-shadow"/><path class="kjmig_qpk wm-k"/><path class="hnamav36t wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-off-engrave" /></template>
