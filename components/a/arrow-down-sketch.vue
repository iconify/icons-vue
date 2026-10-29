<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bozexkkag.css';
import '../../css/w/wdmalj20d.css';
import '../../css/q/q1z_2oboi.css';
import '../../css/c/c4e2--9os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bozexkkag wm-k"/><path class="wdmalj20d wm-a"/><path class="q1z_2oboi wm-k"/><path class="c4e2--9os wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-down-sketch" /></template>
