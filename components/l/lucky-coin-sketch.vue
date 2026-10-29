<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mu6mtxttg.css';
import '../../css/y/y7bfgsbaj.css';
import '../../css/p/poniohbkw.css';
import '../../css/r/rol97abdw.css';
import '../../css/q/q4l2ldtwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mu6mtxttg wm-k"/><path class="wm-k y7bfgsbaj"/><path class="poniohbkw wm-k"/><path class="rol97abdw wm-k"/><path class="q4l2ldtwl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lucky-coin-sketch" /></template>
