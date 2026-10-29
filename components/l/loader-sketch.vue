<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qjbdfqb6h.css';
import '../../css/e/e7th9kyis.css';
import '../../css/x/x4_zs5rtw.css';
import '../../css/l/lpsygpfiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qjbdfqb6h wm-k"/><path class="e7th9kyis wm-a"/><path class="wm-k x4_zs5rtw"/><path class="lpsygpfiq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:loader-sketch" /></template>
