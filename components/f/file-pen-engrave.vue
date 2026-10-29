<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gn2-np9dc.css';
import '../../css/g/gwmckxxys.css';
import '../../css/x/xzvv5ocpg.css';
import '../../css/x/xqfxjetfb.css';
import '../../css/k/k1xan88pf.css';
import '../../css/z/z4bbp2bhq.css';
import '../../css/s/sava3rbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gn2-np9dc wm-k"/><path class="gwmckxxys wm-a"/><path class="wm-s xzvv5ocpg"/><path class="wm-shadow xqfxjetfb"/><path class="k1xan88pf wm-k"/><path class="wm-a z4bbp2bhq"/><path class="sava3rbel wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-pen-engrave" /></template>
