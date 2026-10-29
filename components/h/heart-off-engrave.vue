<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/ooav_l3zk.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/c/cl8daubuk.css';
import '../../css/q/qvra2koks.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ooav_l3zk wm-k"/><path class="ol-kpp5cg wm-s"/><path class="cl8daubuk wm-shadow"/><path class="qvra2koks wm-k"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-off-engrave" /></template>
