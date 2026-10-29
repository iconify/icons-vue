<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q0zjfeb9r.css';
import '../../css/k/kz6nbfeim.css';
import '../../css/u/ucexqlbld.css';
import '../../css/l/ly5598bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q0zjfeb9r wm-k"/><path class="kz6nbfeim wm-shadow"/><path class="ucexqlbld wm-k"/><path class="ly5598bwp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-check-big-engrave" /></template>
