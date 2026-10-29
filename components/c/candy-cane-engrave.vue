<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lne6ksbmw.css';
import '../../css/r/rk2-atb8x.css';
import '../../css/k/k4kerw0_e.css';
import '../../css/u/uya6wcbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lne6ksbmw wm-k"/><path class="rk2-atb8x wm-shadow"/><path class="k4kerw0_e wm-k"/><path class="uya6wcbfz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-cane-engrave" /></template>
