<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lgreg-b0h.css';
import '../../css/t/tejekv0yd.css';
import '../../css/g/gp-44obuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lgreg-b0h wm-k"/><path class="tejekv0yd wm-k"/><path class="gp-44obuf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crosshair-sketch" /></template>
