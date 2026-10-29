<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pk375cb2c.css';
import '../../css/r/rnvgfonpn.css';
import '../../css/s/ssx8dqarr.css';
import '../../css/w/wqssnhx9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pk375cb2c wm-k"/><path class="rnvgfonpn wm-a"/><path class="ssx8dqarr wm-k"/><path class="wm-a wqssnhx9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-right-sketch" /></template>
