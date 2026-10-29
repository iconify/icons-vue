<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y_jacfocb.css';
import '../../css/y/y2i2crbcm.css';
import '../../css/o/ocoockb2g.css';
import '../../css/a/ax14dsbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y_jacfocb"/><path class="wm-shadow y2i2crbcm"/><path class="ocoockb2g"/><path class="ax14dsbgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-engrave" /></template>
