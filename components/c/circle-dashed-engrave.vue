<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/huw4-tbyz.css';
import '../../css/x/xv4sdqbgf.css';
import '../../css/o/o-fwz22nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="huw4-tbyz"/><path class="wm-shadow xv4sdqbgf"/><path class="o-fwz22nq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-dashed-engrave" /></template>
