<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wrzg7sb4i.css';
import '../../css/j/j7rx7-6xl.css';
import '../../css/m/muiqo2blt.css';
import '../../css/n/n0z0dgety.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wrzg7sb4i"/><path class="j7rx7-6xl wm-a"/><path class="muiqo2blt wm-k"/><path class="n0z0dgety wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:copy-check-sketch" /></template>
