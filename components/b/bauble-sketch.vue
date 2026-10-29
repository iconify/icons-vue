<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/owpzfgb8d.css';
import '../../css/d/dsshy_bnq.css';
import '../../css/z/z0pihbb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="owpzfgb8d wm-a"/><path class="dsshy_bnq wm-k"/><path class="wm-a z0pihbb7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bauble-sketch" /></template>
