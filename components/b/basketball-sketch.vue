<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bc2a5pb0l.css';
import '../../css/t/timyirbcb.css';
import '../../css/l/lf5_obwyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bc2a5pb0l"/><path class="timyirbcb wm-k"/><path class="lf5_obwyo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:basketball-sketch" /></template>
