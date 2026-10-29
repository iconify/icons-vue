<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xm3_7gb0y.css';
import '../../css/y/y6er037_f.css';
import '../../css/g/gitu83bla.css';
import '../../css/a/azlmfgbpz.css';
import '../../css/v/vu-t8mz1s.css';
import '../../css/b/bx2-xs7ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xm3_7gb0y"/><path class="wm-a y6er037_f"/><path class="gitu83bla wm-shadow"/><path class="azlmfgbpz wm-k"/><path class="vu-t8mz1s wm-k"/><path class="bx2-xs7ey wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:home-engrave" /></template>
