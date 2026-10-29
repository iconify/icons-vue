<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lwz7j4b-a.css';
import '../../css/d/dv0pewh6k.css';
import '../../css/n/n-ttdbbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lwz7j4b-a wm-deco"/><path class="dv0pewh6k wm-k"/><path class="n-ttdbbjs wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lamp-sketch" /></template>
