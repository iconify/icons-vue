<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uk0viebcn.css';
import '../../css/q/qwoa4ibhw.css';
import '../../css/y/y3_5exb-s.css';
import '../../css/i/ih32s4bkl.css';
import '../../css/v/v1kfzlb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uk0viebcn wm-k"/><path class="qwoa4ibhw wm-a"/><path class="wm-shadow y3_5exb-s"/><path class="ih32s4bkl wm-k"/><path class="v1kfzlb7a wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:link-engrave" /></template>
