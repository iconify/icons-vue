<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vwx_dcpll.css';
import '../../css/v/vs3_2yq5q.css';
import '../../css/z/zbms0lbwh.css';
import '../../css/e/ea_szbbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="vwx_dcpll"/><path class="vs3_2yq5q wm-a"/><path class="zbms0lbwh"/><path class="ea_szbbks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flag-checkered-duo" /></template>
