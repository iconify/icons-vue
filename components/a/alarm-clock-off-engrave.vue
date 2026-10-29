<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e5emcvbhr.css';
import '../../css/s/samcl6ghe.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/m/m--blzueu.css';
import '../../css/t/tjmki8x4n.css';
import '../../css/t/t1khfhdyn.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e5emcvbhr wm-k"/><path class="samcl6ghe wm-a"/><path class="ol-kpp5cg wm-s"/><path class="m--blzueu wm-shadow"/><path class="tjmki8x4n wm-k"/><path class="t1khfhdyn wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-off-engrave" /></template>
