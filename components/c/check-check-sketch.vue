<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k5ukfzb1l.css';
import '../../css/v/v3xk6yicn.css';
import '../../css/l/l7-nltbjq.css';
import '../../css/t/tstc18bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k5ukfzb1l wm-k"/><path class="v3xk6yicn wm-a"/><path class="l7-nltbjq wm-k"/><path class="tstc18bcg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-check-sketch" /></template>
