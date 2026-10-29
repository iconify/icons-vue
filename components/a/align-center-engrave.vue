<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xouepfbxt.css';
import '../../css/o/o75np-b8h.css';
import '../../css/p/p1-mhho-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xouepfbxt"/><path class="o75np-b8h wm-shadow"/><path class="p1-mhho-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-center-engrave" /></template>
