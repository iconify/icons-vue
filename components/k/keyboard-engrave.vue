<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uw8k2ccxn.css';
import '../../css/n/naiqmubbw.css';
import '../../css/m/m2gtrdezm.css';
import '../../css/a/a_-f_rbjf.css';
import '../../css/n/n0-6-ccsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uw8k2ccxn wm-k"/><path class="naiqmubbw wm-k"/><path class="m2gtrdezm wm-shadow"/><path class="a_-f_rbjf wm-k"/><path class="n0-6-ccsd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:keyboard-engrave" /></template>
