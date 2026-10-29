<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oelxptzlr.css';
import '../../css/c/cz8zsdbys.css';
import '../../css/g/gitu83bla.css';
import '../../css/a/azlmfgbpz.css';
import '../../css/v/vu-t8mz1s.css';
import '../../css/y/yew85ogsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oelxptzlr wm-k"/><path class="cz8zsdbys wm-a"/><path class="gitu83bla wm-shadow"/><path class="azlmfgbpz wm-k"/><path class="vu-t8mz1s wm-k"/><path class="wm-a yew85ogsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:house-wifi-engrave" /></template>
