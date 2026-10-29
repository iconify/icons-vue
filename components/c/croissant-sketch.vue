<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/ld14kd3fo.css';
import '../../css/k/kj3ej9b7p.css';
import '../../css/h/hy_wfebxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ld14kd3fo wm-k"/><path class="kj3ej9b7p wm-k"/><path class="hy_wfebxz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:croissant-sketch" /></template>
