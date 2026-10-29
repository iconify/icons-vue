<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vwgy1sbhs.css';
import '../../css/u/uel4uba9h.css';
import '../../css/b/bht756bnp.css';
import '../../css/g/g136touho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vwgy1sbhs wm-k"/><path class="uel4uba9h wm-shadow"/><path class="bht756bnp wm-k"/><path class="g136touho wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:app-window-engrave" /></template>
