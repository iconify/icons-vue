<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u_jv868wi.css';
import '../../css/b/b46u89b7h.css';
import '../../css/v/v8bw9nbrg.css';
import '../../css/l/lhr7mp78x.css';
import '../../css/r/rad68db9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u_jv868wi wm-k"/><path class="b46u89b7h wm-a"/><path class="v8bw9nbrg wm-shadow"/><path class="lhr7mp78x wm-k"/><path class="rad68db9z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-rain-wind-engrave" /></template>
