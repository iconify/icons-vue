<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dn3saf1hp.css';
import '../../css/b/bentd_y0y.css';
import '../../css/s/stx585s_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dn3saf1hp"/><path class="bentd_y0y"/><path class="stx585s_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-fork-sketch" /></template>
