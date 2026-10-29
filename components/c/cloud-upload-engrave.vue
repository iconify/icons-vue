<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sxie_rsic.css';
import '../../css/w/wm_kbibqc.css';
import '../../css/y/y7q976lkn.css';
import '../../css/m/m2ebxhp-u.css';
import '../../css/g/gpzldrb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sxie_rsic wm-k"/><path class="wm-s wm_kbibqc"/><path class="wm-shadow y7q976lkn"/><path class="m2ebxhp-u wm-k"/><path class="gpzldrb9z wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-upload-engrave" /></template>
