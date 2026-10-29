<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e8mhx6bnd.css';
import '../../css/h/hpjvobbts.css';
import '../../css/o/orupijbnu.css';
import '../../css/h/hnvjbpuwe.css';
import '../../css/g/gav9x_bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e8mhx6bnd wm-k"/><path class="hpjvobbts wm-a"/><path class="orupijbnu wm-shadow"/><path class="hnvjbpuwe wm-k"/><path class="gav9x_bhv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:log-in-engrave" /></template>
