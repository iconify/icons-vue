<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m19lpcb0d.css';
import '../../css/t/tf6q4k9qf.css';
import '../../css/p/puozkrmyl.css';
import '../../css/u/urb3kpbld.css';
import '../../css/i/idk2wtbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m19lpcb0d wm-k"/><path class="tf6q4k9qf wm-a"/><path class="puozkrmyl wm-shadow"/><path class="urb3kpbld wm-k"/><path class="idk2wtbbi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:droplets-engrave" /></template>
