<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vwus5_bte.css';
import '../../css/y/yyzxjob8s.css';
import '../../css/a/acri1k30f.css';
import '../../css/e/ex-7uccti.css';
import '../../css/m/mikouibnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vwus5_bte wm-k"/><path class="wm-a yyzxjob8s"/><path class="acri1k30f wm-shadow"/><path class="ex-7uccti wm-k"/><path class="mikouibnu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:credit-card-engrave" /></template>
