<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w3dl34bcg.css';
import '../../css/a/at5oncb-d.css';
import '../../css/g/gndq0ebyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w3dl34bcg"/><path class="at5oncb-d wm-shadow"/><path class="gndq0ebyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dumbbell-engrave" /></template>
