<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/naz7nhbla.css';
import '../../css/q/qwyktibri.css';
import '../../css/o/onacwcrjs.css';
import '../../css/p/px7dfaclp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="naz7nhbla"/><path class="qwyktibri wm-a"/><path class="onacwcrjs wm-k"/><path class="px7dfaclp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:backpack-sketch" /></template>
