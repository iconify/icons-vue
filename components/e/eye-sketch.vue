<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z3nm_s4sb.css';
import '../../css/m/mqdjwcc2h.css';
import '../../css/z/z-pktbist.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z3nm_s4sb"/><path class="mqdjwcc2h wm-k"/><path class="wm-a z-pktbist"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:eye-sketch" /></template>
