<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q8n93xt-z.css';
import '../../css/h/h3yw59bbl.css';
import '../../css/u/uetiicn5o.css';
import '../../css/v/vxpt0hg7g.css';
import '../../css/e/esasw0x6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q8n93xt-z"/><path class="h3yw59bbl wm-k"/><path class="uetiicn5o wm-a"/><path class="vxpt0hg7g wm-k"/><path class="esasw0x6u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:glass-water-sketch" /></template>
