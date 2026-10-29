<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f0dzfwbnn.css';
import '../../css/e/eiqx-rb5c.css';
import '../../css/f/fs0pnm_2d.css';
import '../../css/w/whk4pe4jr.css';
import '../../css/w/w4f1phn-n.css';
import '../../css/z/zegtxvsso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f0dzfwbnn wm-k"/><path class="eiqx-rb5c wm-a"/><path class="fs0pnm_2d wm-shadow"/><path class="whk4pe4jr wm-k"/><path class="w4f1phn-n wm-a"/><path class="wm-k zegtxvsso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:burger-engrave" /></template>
