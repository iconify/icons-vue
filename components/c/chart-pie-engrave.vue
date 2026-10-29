<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/et10ct7zx.css';
import '../../css/x/xrbipbw_x.css';
import '../../css/b/brflxoyzi.css';
import '../../css/d/d7j47q-dh.css';
import '../../css/g/gcc_iacbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="et10ct7zx wm-k"/><path class="wm-a xrbipbw_x"/><path class="brflxoyzi wm-shadow"/><path class="d7j47q-dh wm-k"/><path class="gcc_iacbm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-pie-engrave" /></template>
