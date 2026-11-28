<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sb-u7hbtr.css';
import '../../css/r/rvi3m3bvn.css';
import '../../css/t/tkcc8g1nv.css';
import '../../css/x/xui_jhgnu.css';
import '../../css/s/sj9w6gbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sb-u7hbtr"/><path class="rvi3m3bvn"/><path class="tkcc8g1nv"/><path class="xui_jhgnu"/><path class="sj9w6gbtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gamepad" /></template>
