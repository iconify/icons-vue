<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jsrzdnbpw.css';
import '../../css/a/ansa2ab2z.css';
import '../../css/g/g1l958bde.css';
import '../../css/d/dzjyg2btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jsrzdnbpw wm-a"/><path class="ansa2ab2z wm-k"/><path class="g1l958bde wm-k"/><path class="dzjyg2btd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-scatter-sketch" /></template>
