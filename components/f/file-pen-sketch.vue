<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rxrq2dbzm.css';
import '../../css/c/cuu4u-hgm.css';
import '../../css/w/wdn9m_beo.css';
import '../../css/u/ux1uh-02v.css';
import '../../css/m/mip4_abrl.css';
import '../../css/d/d5tl-zbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rxrq2dbzm"/><path class="cuu4u-hgm wm-k"/><path class="wdn9m_beo wm-s"/><path class="ux1uh-02v wm-k"/><path class="mip4_abrl wm-a"/><path class="d5tl-zbhg wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-pen-sketch" /></template>
