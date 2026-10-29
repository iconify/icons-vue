<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x_qr1h6di.css';
import '../../css/e/es4j3mt3g.css';
import '../../css/h/hab5ou_zs.css';
import '../../css/e/e3yj0zblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="x_qr1h6di"/><path class="es4j3mt3g wm-k"/><path class="hab5ou_zs wm-k"/><path class="e3yj0zblf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:certificate-sketch" /></template>
