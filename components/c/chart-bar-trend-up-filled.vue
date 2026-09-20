<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iqif41bmh.css';
import '../../css/d/dvg04bcea.css';
import '../../css/b/bl4zoxpll.css';
import '../../css/a/a2ynllugw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><rect class="iqif41bmh"/><rect class="dvg04bcea"/><rect class="bl4zoxpll"/><path class="a2ynllugw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart-bar-trend-up-filled" /></template>
