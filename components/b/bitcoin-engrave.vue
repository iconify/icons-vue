<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/se42xybiv.css';
import '../../css/f/fksg71bpx.css';
import '../../css/t/t0spev3hn.css';
import '../../css/d/dfr8kabwp.css';
import '../../css/o/omdwggbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="se42xybiv wm-k"/><path class="fksg71bpx wm-a"/><path class="t0spev3hn wm-shadow"/><path class="dfr8kabwp wm-k"/><path class="omdwggbcq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bitcoin-engrave" /></template>
