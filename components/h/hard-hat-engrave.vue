<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hoxpu_2cg.css';
import '../../css/x/xcvq1hf3w.css';
import '../../css/l/lv38v7jih.css';
import '../../css/h/hcaie_vox.css';
import '../../css/m/mce9chbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hoxpu_2cg wm-k"/><path class="wm-a xcvq1hf3w"/><path class="lv38v7jih wm-shadow"/><path class="hcaie_vox wm-k"/><path class="mce9chbnc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hard-hat-engrave" /></template>
