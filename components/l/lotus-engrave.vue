<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m_nwy9b3k.css';
import '../../css/l/lamdb9wip.css';
import '../../css/e/ex6u24bpk.css';
import '../../css/u/ul2a8pijw.css';
import '../../css/i/i2qnw-bhf.css';
import '../../css/i/iayt--bmg.css';
import '../../css/v/vvd7iabnl.css';
import '../../css/x/xslfg2evh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m_nwy9b3k wm-k"/><path class="lamdb9wip wm-a"/><path class="ex6u24bpk wm-s"/><path class="ul2a8pijw wm-shadow"/><path class="i2qnw-bhf wm-k"/><path class="iayt--bmg wm-k"/><path class="vvd7iabnl wm-a"/><path class="wm-s xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lotus-engrave" /></template>
